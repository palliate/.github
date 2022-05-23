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
* [resources](/development/resources)

[build](/development/build) is special in that it may only be defined within one `config.toml` file within the project. This means you should never define this in a plugin or in the library.

Example:
```toml
[build]
project = "test"

[config.help]
type    = "bool"
cli     = true
default = false

[resources.icon]
path    = "app/icon.ico"
```