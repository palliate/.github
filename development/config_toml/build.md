---
layout: default
title: build
has_children: false
parent: config.toml
grand_parent: Development
permalink: /development/build
---

# build table

Subtables of `build` define metadata for a (sub)project.

## Format
```toml
# pull metadata for a project named project_name
[build.project_name]
  # type of this build
  # can be either application, library or plugin
  # only one application and one library build may exist
  # type: string
  type = "application"

  # current version number for this project
  # please use semantic versioning for this
  # see https://semver.org/
  # type: string
  version = "v0.0.1"

  # specify root directory relative to this config file
  # useful if this file isn't located at the project's root
  #
  # should point to the directory containing the .git folder
  # if git is enabled
  # type:    string
  # default: "."
  root = "../../"

  # include information about the local git repository's state
  # type:    bool
  # default: true
  git = true
```

might generate something like
```cpp
#pragma once
#include <optional>
#include <string_view>

namespace config {
namespace build {
struct build_info {
  struct git_info {
    std::string_view remote_url;
    std::string_view web_url;
    std::string_view branch;
    std::string_view commit;
    std::string_view commit_short;
    bool modified;
  };

  std::string_view project;
  std::string_view root;
  std::string_view version;
  const std::optional<git_info> git;
};

static const build_info application = {
    {.name = "project_name",
     .root = R"(/path/to/this/project)",
     .version = "v0.0.1",
     .git = {{.remote_url = R"(git@github.com:user/repo.git)",
              .web_url = R"(https://github.com/user/repo)",
              .branch = "master",
              .commit = "f4630ba7ce9a4c89aecbb42a276182b9f310130a",
              .commit_short = "f4630ba",
              .modified = true}}}},
};

static const build_info library = {
};

static const build_info plugins[] = {
};
}  // namespace build
}  // namespace config

```