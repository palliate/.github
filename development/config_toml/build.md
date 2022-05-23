---
layout: default
title: build
has_children: false
parent: config.toml
permalink: /development/build
---

# build table

The `build` table is special in that it may only be defined within one `config.toml` file within the project. This means you should never define this in a plugin or in the library.

Think of this table as project wide code generation settings.

## Format
```toml
[build]
  # the name of the current project
  # type:    string
  project = "project-name"

  # include information about the local git repository's state
  # type:    bool
  # default: true
  git = true
```

might generate something like
```cpp
#pragma once
#include <string_view>

namespace config {
  constexpr std::string_view project = "project-name";
  constexpr std::string_view project_root = R"(/local/project/directory)";

  constexpr std::string_view remote_url = R"(git@github.com:user/repo.git)";
  constexpr std::string_view web_url = R"(https://github.com/user/repo)";
  constexpr std::string_view branch = "master";
  constexpr std::string_view commit = "7bfe2bd8571425f9cf77e809fe3fe7e145e2db11";
  constexpr std::string_view commit_short = "7bfe2bd";
  constexpr bool modified = true;
}  // namespace config
```