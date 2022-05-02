---
title: utf8_reader_interface
parent: Classes
grand_parent: libpalliate
layout: default
---

# utf8_reader_interface






`#include <toml.hpp>`

Inherited by [utf8_reader< T >](/libpalliate/generated/Classes/classutf8__reader)

## Public Functions

|                | Name           |
| -------------- | -------------- |
| virtual const [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[source_path_ptr](/libpalliate/generated/Files/source__region_8h#using-source-path-ptr) & | **[source_path](/libpalliate/generated/Classes/structutf8__reader__interface#function-source-path)**() const =0 |
| virtual const [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[utf8_codepoint](/libpalliate/generated/Classes/structutf8__codepoint) * | **[read_next](/libpalliate/generated/Classes/structutf8__reader__interface#function-read-next)**() =0 |
| virtual [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) bool | **[peek_eof](/libpalliate/generated/Classes/structutf8__reader__interface#function-peek-eof)**() const =0 |
| virtual [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) optional< parse_error > && | **[error](/libpalliate/generated/Classes/structutf8__reader__interface#function-error)**() =0 |
| virtual | **[~utf8_reader_interface](/libpalliate/generated/Classes/structutf8__reader__interface#function-~utf8-reader-interface)**() =default |
| virtual const [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[source_path_ptr](/libpalliate/generated/Files/source__region_8h#using-source-path-ptr) & | **[source_path](/libpalliate/generated/Classes/structutf8__reader__interface#function-source-path)**() const =0 |
| virtual const [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[utf8_codepoint](/libpalliate/generated/Classes/structutf8__codepoint) * | **[read_next](/libpalliate/generated/Classes/structutf8__reader__interface#function-read-next)**() =0 |
| virtual [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) bool | **[peek_eof](/libpalliate/generated/Classes/structutf8__reader__interface#function-peek-eof)**() const =0 |
| virtual [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) optional< parse_error > && | **[error](/libpalliate/generated/Classes/structutf8__reader__interface#function-error)**() =0 |
| virtual | **[~utf8_reader_interface](/libpalliate/generated/Classes/structutf8__reader__interface#function-~utf8-reader-interface)**() =default |

## Public Functions Documentation

### function source_path

```cpp
virtual const TOML_NODISCARDsource_path_ptr & source_path() const =0
```


**Reimplemented by**: [utf8_reader::source_path](/libpalliate/generated/Classes/classutf8__reader#function-source-path), [utf8_reader::source_path](/libpalliate/generated/Classes/classutf8__reader#function-source-path)


### function read_next

```cpp
virtual const TOML_NODISCARDutf8_codepoint * read_next() =0
```


**Reimplemented by**: [utf8_reader::read_next](/libpalliate/generated/Classes/classutf8__reader#function-read-next), [utf8_reader::read_next](/libpalliate/generated/Classes/classutf8__reader#function-read-next)


### function peek_eof

```cpp
virtual TOML_NODISCARD bool peek_eof() const =0
```


**Reimplemented by**: [utf8_reader::peek_eof](/libpalliate/generated/Classes/classutf8__reader#function-peek-eof), [utf8_reader::peek_eof](/libpalliate/generated/Classes/classutf8__reader#function-peek-eof)


### function error

```cpp
virtual TOML_NODISCARD optional< parse_error > && error() =0
```


**Reimplemented by**: [utf8_reader::error](/libpalliate/generated/Classes/classutf8__reader#function-error), [utf8_reader::error](/libpalliate/generated/Classes/classutf8__reader#function-error)


### function ~utf8_reader_interface

```cpp
virtual ~utf8_reader_interface() =default
```


### function source_path

```cpp
virtual const TOML_NODISCARDsource_path_ptr & source_path() const =0
```


**Reimplemented by**: [utf8_reader::source_path](/libpalliate/generated/Classes/classutf8__reader#function-source-path), [utf8_reader::source_path](/libpalliate/generated/Classes/classutf8__reader#function-source-path)


### function read_next

```cpp
virtual const TOML_NODISCARDutf8_codepoint * read_next() =0
```


**Reimplemented by**: [utf8_reader::read_next](/libpalliate/generated/Classes/classutf8__reader#function-read-next), [utf8_reader::read_next](/libpalliate/generated/Classes/classutf8__reader#function-read-next)


### function peek_eof

```cpp
virtual TOML_NODISCARD bool peek_eof() const =0
```


**Reimplemented by**: [utf8_reader::peek_eof](/libpalliate/generated/Classes/classutf8__reader#function-peek-eof), [utf8_reader::peek_eof](/libpalliate/generated/Classes/classutf8__reader#function-peek-eof)


### function error

```cpp
virtual TOML_NODISCARD optional< parse_error > && error() =0
```


**Reimplemented by**: [utf8_reader::error](/libpalliate/generated/Classes/classutf8__reader#function-error), [utf8_reader::error](/libpalliate/generated/Classes/classutf8__reader#function-error)


### function ~utf8_reader_interface

```cpp
virtual ~utf8_reader_interface() =default
```



_Automatically updated on 2022-05-02 at 01:42:11 +0000._