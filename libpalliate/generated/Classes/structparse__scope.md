---
title: parse_scope
parent: Classes
grand_parent: libpalliate
layout: default
---

# parse_scope






`#include <toml.hpp>`

## Public Functions

|                | Name           |
| -------------- | -------------- |
| [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor) | **[parse_scope](/libpalliate/generated/Classes/structparse__scope#function-parse-scope)**(std::string_view & current_scope, std::string_view new_scope) |
| | **[~parse_scope](/libpalliate/generated/Classes/structparse__scope#function-~parse-scope)**() |
| | **[TOML_DELETE_DEFAULTS](/libpalliate/generated/Classes/structparse__scope#function-toml-delete-defaults)**([parse_scope](/libpalliate/generated/Classes/structparse__scope) ) |
| [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor) | **[parse_scope](/libpalliate/generated/Classes/structparse__scope#function-parse-scope)**(std::string_view & current_scope, std::string_view new_scope) |
| | **[~parse_scope](/libpalliate/generated/Classes/structparse__scope#function-~parse-scope)**() |
| | **[TOML_DELETE_DEFAULTS](/libpalliate/generated/Classes/structparse__scope#function-toml-delete-defaults)**([parse_scope](/libpalliate/generated/Classes/structparse__scope) ) |

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| std::string_view & | **[storage_](/libpalliate/generated/Classes/structparse__scope#variable-storage-)**  |
| std::string_view | **[parent_](/libpalliate/generated/Classes/structparse__scope#variable-parent-)**  |

## Public Functions Documentation

### function parse_scope

```cpp
inline explicit TOML_NODISCARD_CTOR parse_scope(
    std::string_view & current_scope,
    std::string_view new_scope
)
```


### function ~parse_scope

```cpp
inline ~parse_scope()
```


### function TOML_DELETE_DEFAULTS

```cpp
TOML_DELETE_DEFAULTS(
    parse_scope 
)
```


### function parse_scope

```cpp
inline explicit TOML_NODISCARD_CTOR parse_scope(
    std::string_view & current_scope,
    std::string_view new_scope
)
```


### function ~parse_scope

```cpp
inline ~parse_scope()
```


### function TOML_DELETE_DEFAULTS

```cpp
TOML_DELETE_DEFAULTS(
    parse_scope 
)
```


## Public Attributes Documentation

### variable storage_

```cpp
std::string_view & storage_;
```


### variable parent_

```cpp
std::string_view parent_;
```



_Automatically updated on 2022-05-02 at 01:42:07 +0000._