---
layout: default
title: config
has_children: false
parent: config.toml
permalink: /development/config
---

# config table

Subtables of `config` will be used to generate code which allows for easy conversion from and into toml. These files will be placed in `<build>/generated/config/` and use the subclass's name.

If a variable within one of these subtables has `cli = true` defined, an entry within `<build>/generated/cli.h` will be added. 

## Format
```toml
# class name within config namespace
[config.name]
  # place a comment at the node root
  # type: string, None
  comment = "Comment for this node" # optional

  # include the listed files
  # type: array<string>, None
  requires = ["config/uuid.h", "cstdbool"] # optional

  # define variable with name setting
  # names across CLI arguments should be unique
  # since they will be used as longopt key
  [config.name.setting]
    # c++ type of this setting
    # type:    string
    type = "int"

    # place a comment at this setting
    # will be used for --help if cli = true
    # type: string, None
    comment = "Setting comment" # optional

    # whether this setting should be written to the config file
    # set this to false for non-persistant cli options
    # type:    bool, None
    # default: true
    save = true # optional
   
    # whether this setting should be overridable using command line arguments
    # type:    bool, None
    # default: false
    cli = true # optional

    # shorthand command for command line arguments
    # should only be set if cli=true
    # type:    string (limited to one character!), None
    shorthand = "s" # optional

    # default value to use
    # if none is given this setting
    # interpreted as inline c++ if type is array<string>
    # type:    array<string>, string, bool, int, None
    default = ["int{}"] # optional
```

This would generate

```cpp
// <build>/generated/config/name.h

#pragma once
#include <toml11/toml.hpp>
#include <config/uuid.h>
#include <cstdbool>

namespace config {
struct name {
  int setting = int{};

  void from_toml(const toml::value& node) {
    setting = toml::find<int>(node, "setting");
  }

  toml::basic_value<toml::preserve_comments> into_toml() const {
    toml::basic_value<toml::preserve_comments> _setting(setting);

    _setting.comments().push_back("Setting comment");

    toml::basic_value<toml::preserve_comments> node{{"setting", _setting}};
    table.comments().push_back("Comment for this node");
    return node;
  }
};
}  // namespace config

```
and
```cpp
// <build>/generated/cli.h
#pragma once
#include <unordered_map>
#include <string>
#include <variant>

namespace config {
  const std::unordered_map<std::string, config::cli_option> cli_options = {
    {"config.name.setting",
      {.name = "setting",
       .comment = "Setting comment",
       .default_value = int{},
       .shorthand = "s"
      }
    },
    // ...
  }
} // namespace config
```