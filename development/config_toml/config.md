---
layout: default
title: config
has_children: false
parent: config.toml
grand_parent: Development
permalink: /development/config
---

# config table

Subtables of `config` will be used to generate code which allows for easy conversion from and into toml. These files will be placed in `<build>/generated/config/` and use the subclass's name.

If a variable within one of these subtables has `cli = true` defined, an entry within `<build>/generated/cli.h` will be added. 

## Format
```toml
# name of this config
# the class and filename of the generated header
# will be derived from this
# in this example it'd generated
# /config/foobar.h which contains the class config::foobar
[config.foobar]
  # place a comment at the node root
  # type: string, None
  comment = "Comment for this node" # optional

  # include the listed headers
  # type: array<string>, None
  requires = ["config/uuid.h", "cstdbool"] # optional

  # define variable with name setting

  [[config.foobar.settings]]
    # name for this setting
    # names within settings of this config need to be unique
    # names across CLI arguments need to be unique
    # since they will be used as longopt key
    # type:    string
    name = "foo"

    # c++ type of this setting
    # type:    string
    type = "int"

    # place a comment at this setting
    # will be used for --help if cli = true
    # can be multiline
    # type:    string, None
    comment = "Setting comment" # optional

    # whether this setting should be written to the config file
    # set this to false for non-persistent cli options
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
    # if none is given this setting will be considered optional
    # interpreted as inline c++ if type is array<string>
    # type:    array<string>, string, bool, int, None
    default = ["int{}"] # optional

  # minimal example
  [[config.foobar.settings]]
    type = "int"
    name = "minimal"
```

This would generate

```cpp
// <build>/generated/config/foobar.h

#pragma once
#include <toml11/toml.hpp>
#include <config/uuid.h>
#include <cstdbool>

namespace config {
struct  {
    int foo = int{};
    int minimal;

  void from_toml(const toml::value& v) {
    foo = toml::find_or<int>(v, "foo", int{});
    minimal = toml::find<int>(v, "minimal");
    
  }

  toml::basic_value<toml::preserve_comments> into_toml() const {
    toml::basic_value<toml::preserve_comments> _foo{foo};
    _foo.comments().push_back(R"""(Setting comment)""");
    
    toml::basic_value<toml::preserve_comments> _minimal{minimal};
    
    toml::basic_value<toml::preserve_comments> table{
      {"foo", _foo},
      {"minimal", _minimal},
    };
    table.comments().push_back(R"""(Comment for this node)""");
    return table;
  }
};
}  // namespace config


```
and
```cpp
// <build>/generated/cli.h
#pragma once
#include <string>
#include <unordered_map>
#include <map>
#include <optional>
#include <string_view>

namespace config {
using namespace std::string_view_literals;
struct cli_option {
  std::string_view table;
  std::optional<char const> shorthand;
  std::string_view description = ""sv;
};

static const std::map<char, const std::string> cli_shorthands = {
  // ...
  {'s', "foo"},
  // ...
};

static const std::unordered_map<const std::string, cli_option> cli_map = {
    // ...
    {"foo",
     {
         .table = "foobar"sv,
         .shorthand = 's',
         .description = R"""(Setting comment)"""sv,
     }},
     // ...
};
}  // namespace config

```