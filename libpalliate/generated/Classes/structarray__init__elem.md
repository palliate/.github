---
title: array_init_elem
parent: Classes
grand_parent: libpalliate
layout: default
---

# array_init_elem






`#include <toml.hpp>`

## Public Functions

|                | Name           |
| -------------- | -------------- |
| template <typename T \> <br>[TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor) | **[array_init_elem](/libpalliate/generated/Classes/structarray__init__elem#function-array-init-elem)**(T && val, [value_flags](/libpalliate/generated/Files/toml_8hpp#variable-value-flags) flags =[preserve_source_value_flags](/libpalliate/generated/Files/toml_8hpp#variable-preserve-source-value-flags)) |

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| node_ptr | **[value](/libpalliate/generated/Classes/structarray__init__elem#variable-value)**  |

## Public Functions Documentation

### function array_init_elem

```cpp
template <typename T >
inline TOML_NODISCARD_CTOR array_init_elem(
    T && val,
    value_flags flags =preserve_source_value_flags
)
```


## Public Attributes Documentation

### variable value

```cpp
node_ptr value;
```



_Automatically updated on 2022-05-02 at 01:42:07 +0000._