---
layout: default
title: Factories
has_children: false
parent: plugins
grand_parent: Development
permalink: /development/factories
---

# Factories

In order to add functionality through a plugin the plugin must register to one of the factories.

Currently the following factories are available:

* [logging::endpoint](https://doxygen.palliate.io/structlogging_1_1endpoint.html)

Classes registering to factories need to be configurable, so you'll have to write a [config.toml](/development/config_toml). Here's a minimal example:
```toml
[build.IPoAC]
  type = "plugin"
  version = "v0.0.1"
  git = false

[config.IPoAC]
  comment = "IP over Avian Carrier"
  parent = "transport"

  [[config.IPoAC.settings]]
    name = "enabled"
    type = "bool"
    default = false
    comment = "Enable IPoAC transport."
```
```cpp
#include <transport/server.h>
#include <generated/config/ipoac.h>

namespace transport {
class IPoAC : public server::registrar<IPoAC, config::IPoAC> {
public:
  explicit IPoAC(config_t const& c) : registrar(c) {}
};
}
```

Don't forget to turn on [code generation](/development/config_toml) for the plugin subproject!