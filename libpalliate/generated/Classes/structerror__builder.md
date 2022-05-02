---
title: error_builder
parent: Classes
grand_parent: libpalliate
layout: default
---

# error_builder






`#include <toml.hpp>`

## Public Functions

|                | Name           |
| -------------- | -------------- |
| [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor) | **[error_builder](/libpalliate/generated/Classes/structerror__builder#function-error-builder)**(std::string_view scope) |
| template <typename T \> <br>void | **[append](/libpalliate/generated/Classes/structerror__builder#function-append)**(const T & arg) |
| [TOML_RETURNS_BY_THROWING](/libpalliate/generated/Files/toml_8hpp#define-toml-returns-by-throwing) auto | **[finish](/libpalliate/generated/Classes/structerror__builder#function-finish)**(const [source_position](/libpalliate/generated/Classes/structsource__position) & pos, const [source_path_ptr](/libpalliate/generated/Files/source__region_8h#using-source-path-ptr) & source_path) const |
| | **[TOML_DELETE_DEFAULTS](/libpalliate/generated/Classes/structerror__builder#function-toml-delete-defaults)**([error_builder](/libpalliate/generated/Classes/structerror__builder) ) |
| [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor) | **[error_builder](/libpalliate/generated/Classes/structerror__builder#function-error-builder)**(std::string_view scope) |
| template <typename T \> <br>void | **[append](/libpalliate/generated/Classes/structerror__builder#function-append)**(const T & arg) |
| [TOML_RETURNS_BY_THROWING](/libpalliate/generated/Files/toml_8hpp#define-toml-returns-by-throwing) auto | **[finish](/libpalliate/generated/Classes/structerror__builder#function-finish)**(const [source_position](/libpalliate/generated/Classes/structsource__position) & pos, const [source_path_ptr](/libpalliate/generated/Files/source__region_8h#using-source-path-ptr) & source_path) const |
| | **[TOML_DELETE_DEFAULTS](/libpalliate/generated/Classes/structerror__builder#function-toml-delete-defaults)**([error_builder](/libpalliate/generated/Classes/structerror__builder) ) |

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| constexpr std::size_t | **[buf_size](/libpalliate/generated/Classes/structerror__builder#variable-buf-size)**  |
| char | **[buf](/libpalliate/generated/Classes/structerror__builder#variable-buf)**  |
| char * | **[write_pos](/libpalliate/generated/Classes/structerror__builder#variable-write-pos)**  |
| char *const | **[max_write_pos](/libpalliate/generated/Classes/structerror__builder#variable-max-write-pos)**  |

## Public Functions Documentation

### function error_builder

```cpp
inline TOML_NODISCARD_CTOR error_builder(
    std::string_view scope
)
```


### function append

```cpp
template <typename T >
inline void append(
    const T & arg
)
```


### function finish

```cpp
inline TOML_RETURNS_BY_THROWING auto finish(
    const source_position & pos,
    const source_path_ptr & source_path
) const
```


### function TOML_DELETE_DEFAULTS

```cpp
TOML_DELETE_DEFAULTS(
    error_builder 
)
```


### function error_builder

```cpp
inline TOML_NODISCARD_CTOR error_builder(
    std::string_view scope
)
```


### function append

```cpp
template <typename T >
inline void append(
    const T & arg
)
```


### function finish

```cpp
inline TOML_RETURNS_BY_THROWING auto finish(
    const source_position & pos,
    const source_path_ptr & source_path
) const
```


### function TOML_DELETE_DEFAULTS

```cpp
TOML_DELETE_DEFAULTS(
    error_builder 
)
```


## Public Attributes Documentation

### variable buf_size

```cpp
static constexpr std::size_t buf_size = 512;
```


### variable buf

```cpp
char buf;
```


### variable write_pos

```cpp
char * write_pos = buf;
```


### variable max_write_pos

```cpp
char *const max_write_pos = buf + (buf_size - std::size_t{ 1 });
```



_Automatically updated on 2022-05-02 at 01:42:07 +0000._