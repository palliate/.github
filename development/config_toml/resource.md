---
layout: default
title: resource
has_children: false
parent: config.toml
grand_parent: Development
permalink: /development/resource
---

# resource table
Embeds files into the resulting binary. This is useful for embedding small icons, shader code etc.

## Format
```toml
# places the resource at resource::name
[resource.name]
  # which file to embed
  # type: string
  path = "path/to/file.txt"
  
  # sets the path relative to this config's directory
  # if false path will be considered relative to the project root
  # type: bool
  # default: false
  relative = true # optional
```

Assuming file.txt contains the text `che` this would generate:
```cpp
// <build>/generated/resource.h
#pragma once
#include <cstdint>

namespace config {
namespace resource {
  static constexpr uint8_t name[] = {
    99, 104, 101,
  };
  // ...
} // namespace resource
} // namespace config
```