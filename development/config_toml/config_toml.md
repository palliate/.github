---
layout: default
title: config.toml
has_children: true
nav_order: 22
parent: Development
permalink: /development/config_toml
---

# config.toml

Throughout the source tree you will find files called [config.toml](https://github.com/search?q=filename%3Aconfig.toml+repo%3Apalliate%2Fpalliate+repo%3Apalliate%2Flibpalliate&type=code). These files are collected, parsed and used for code generation during the build process.

This page is meant to document how `config.toml` files are used - if you are interested in the actual implementation check out [palliate/config](https://github.com/palliate/palliate/tree/master/config).

## Format

Each `config.toml` file may define subtables within these tables:
* [config](/development/config)
* [resource](/development/resource)
* [build](/development/build)

Example:
```toml
[build.test]
  version = "v0.1.0"

[config.foobar]
  [[config.foobar.settings]]
    name = "foo"
    type = "bool"
    cli = true
    default = false

[resource.icon]
path    = "app/icon.ico"
```