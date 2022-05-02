---
title: utf8_reader
parent: Classes
grand_parent: libpalliate
layout: default
---

# utf8_reader



 [More...](#detailed-description)


`#include <toml.hpp>`

Inherits from [utf8_reader_interface](/libpalliate/generated/Classes/structutf8__reader__interface)

## Public Functions

|                | Name           |
| -------------- | -------------- |
| template <typename U ,typename String  =std::string_view\> <br>[TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor) | **[utf8_reader](/libpalliate/generated/Classes/classutf8__reader#function-utf8-reader)**(U && source, String && source_path ={}) |
| virtual const [TOML_PURE_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-inline-getter)[source_path_ptr](/libpalliate/generated/Files/source__region_8h#using-source-path-ptr) & | **[source_path](/libpalliate/generated/Classes/classutf8__reader#function-source-path)**() const |
| virtual const [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[utf8_codepoint](/libpalliate/generated/Classes/structutf8__codepoint) * | **[read_next](/libpalliate/generated/Classes/classutf8__reader#function-read-next)**() |
| virtual [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) bool | **[peek_eof](/libpalliate/generated/Classes/classutf8__reader#function-peek-eof)**() const |
| virtual [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) optional< parse_error > && | **[error](/libpalliate/generated/Classes/classutf8__reader#function-error)**() |
| template <typename U ,typename String  =std::string_view\> <br>[TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor) | **[utf8_reader](/libpalliate/generated/Classes/classutf8__reader#function-utf8-reader)**(U && source, String && source_path ={}) |
| virtual const [TOML_PURE_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-inline-getter)[source_path_ptr](/libpalliate/generated/Files/source__region_8h#using-source-path-ptr) & | **[source_path](/libpalliate/generated/Classes/classutf8__reader#function-source-path)**() const |
| virtual const [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[utf8_codepoint](/libpalliate/generated/Classes/structutf8__codepoint) * | **[read_next](/libpalliate/generated/Classes/classutf8__reader#function-read-next)**() |
| virtual [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) bool | **[peek_eof](/libpalliate/generated/Classes/classutf8__reader#function-peek-eof)**() const |
| virtual [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) optional< parse_error > && | **[error](/libpalliate/generated/Classes/classutf8__reader#function-error)**() |

## Additional inherited members

**Public Functions inherited from [utf8_reader_interface](/libpalliate/generated/Classes/structutf8__reader__interface)**

|                | Name           |
| -------------- | -------------- |
| virtual | **[~utf8_reader_interface](/libpalliate/generated/Classes/structutf8__reader__interface#function-~utf8-reader-interface)**() =default |
| virtual | **[~utf8_reader_interface](/libpalliate/generated/Classes/structutf8__reader__interface#function-~utf8-reader-interface)**() =default |


## Detailed Description

```cpp
template <typename T >
class utf8_reader;
```

## Public Functions Documentation

### function utf8_reader

```cpp
template <typename U ,
typename String  =std::string_view>
inline explicit TOML_NODISCARD_CTOR utf8_reader(
    U && source,
    String && source_path ={}
)
```


### function source_path

```cpp
inline virtual const TOML_PURE_INLINE_GETTERsource_path_ptr & source_path() const
```


**Reimplements**: [utf8_reader_interface::source_path](/libpalliate/generated/Classes/structutf8__reader__interface#function-source-path)


### function read_next

```cpp
inline virtual const TOML_NODISCARDutf8_codepoint * read_next()
```


**Reimplements**: [utf8_reader_interface::read_next](/libpalliate/generated/Classes/structutf8__reader__interface#function-read-next)


### function peek_eof

```cpp
inline virtual TOML_NODISCARD bool peek_eof() const
```


**Reimplements**: [utf8_reader_interface::peek_eof](/libpalliate/generated/Classes/structutf8__reader__interface#function-peek-eof)


### function error

```cpp
inline virtual TOML_NODISCARD optional< parse_error > && error()
```


**Reimplements**: [utf8_reader_interface::error](/libpalliate/generated/Classes/structutf8__reader__interface#function-error)


### function utf8_reader

```cpp
template <typename U ,
typename String  =std::string_view>
inline explicit TOML_NODISCARD_CTOR utf8_reader(
    U && source,
    String && source_path ={}
)
```


### function source_path

```cpp
inline virtual const TOML_PURE_INLINE_GETTERsource_path_ptr & source_path() const
```


**Reimplements**: [utf8_reader_interface::source_path](/libpalliate/generated/Classes/structutf8__reader__interface#function-source-path)


### function read_next

```cpp
inline virtual const TOML_NODISCARDutf8_codepoint * read_next()
```


**Reimplements**: [utf8_reader_interface::read_next](/libpalliate/generated/Classes/structutf8__reader__interface#function-read-next)


### function peek_eof

```cpp
inline virtual TOML_NODISCARD bool peek_eof() const
```


**Reimplements**: [utf8_reader_interface::peek_eof](/libpalliate/generated/Classes/structutf8__reader__interface#function-peek-eof)


### function error

```cpp
inline virtual TOML_NODISCARD optional< parse_error > && error()
```


**Reimplements**: [utf8_reader_interface::error](/libpalliate/generated/Classes/structutf8__reader__interface#function-error)



_Automatically updated on 2022-05-02 at 01:42:07 +0000._