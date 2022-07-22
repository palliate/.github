---
layout: default
title: plugins
parent: Development
nav_order: 35
has_children: true
permalink: /development/plugins
---

# plugins

If you want the plugin's build information and command line arguments to be available to palliate the plugin must be built in-source. For that reason it's highly discouraged to build plugins outside of palliate's source tree.

Plugins should define a build target, for example:
```toml
[build.IPoAC]
  type = "plugin"
  version = "v0.0.1"
  git = false
```

To add functionality plugins must register their classes to [Factories](/development/factories)