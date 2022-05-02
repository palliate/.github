---
title: table_init_pair
parent: Classes
grand_parent: libpalliate
layout: default
---

# table_init_pair






`#include <toml.hpp>`

## Public Functions

|                | Name           |
| -------------- | -------------- |
| template <typename K ,typename V \> <br>[TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor) | **[table_init_pair](/libpalliate/generated/Classes/structtable__init__pair#function-table-init-pair)**(K && k, V && v, [value_flags](/libpalliate/generated/Files/toml_8hpp#variable-value-flags) flags =[preserve_source_value_flags](/libpalliate/generated/Files/toml_8hpp#variable-preserve-source-value-flags)) |

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| toml::key | **[key](/libpalliate/generated/Classes/structtable__init__pair#variable-key)**  |
| node_ptr | **[value](/libpalliate/generated/Classes/structtable__init__pair#variable-value)**  |

## Public Functions Documentation

### function table_init_pair

```cpp
template <typename K ,
typename V >
inline TOML_NODISCARD_CTOR table_init_pair(
    K && k,
    V && v,
    value_flags flags =preserve_source_value_flags
)
```


## Public Attributes Documentation

### variable key

```cpp
toml::key key;
```


### variable value

```cpp
node_ptr value;
```



_Automatically updated on 2022-05-02 at 01:42:11 +0000._