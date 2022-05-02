---
title: utf8_buffered_reader
parent: Classes
grand_parent: libpalliate
layout: default
---

# utf8_buffered_reader






`#include <toml.hpp>`

## Public Functions

|                | Name           |
| -------------- | -------------- |
| [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor) | **[utf8_buffered_reader](/libpalliate/generated/Classes/classutf8__buffered__reader#function-utf8-buffered-reader)**([utf8_reader_interface](/libpalliate/generated/Classes/structutf8__reader__interface) & reader) |
| const [TOML_PURE_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-inline-getter)[source_path_ptr](/libpalliate/generated/Files/source__region_8h#using-source-path-ptr) & | **[source_path](/libpalliate/generated/Classes/classutf8__buffered__reader#function-source-path)**() const |
| const [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[utf8_codepoint](/libpalliate/generated/Classes/structutf8__codepoint) * | **[read_next](/libpalliate/generated/Classes/classutf8__buffered__reader#function-read-next)**() |
| const [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[utf8_codepoint](/libpalliate/generated/Classes/structutf8__codepoint) * | **[step_back](/libpalliate/generated/Classes/classutf8__buffered__reader#function-step-back)**(size_t count) |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) bool | **[peek_eof](/libpalliate/generated/Classes/classutf8__buffered__reader#function-peek-eof)**() const |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) optional< parse_error > && | **[error](/libpalliate/generated/Classes/classutf8__buffered__reader#function-error)**() |
| [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor) | **[utf8_buffered_reader](/libpalliate/generated/Classes/classutf8__buffered__reader#function-utf8-buffered-reader)**([utf8_reader_interface](/libpalliate/generated/Classes/structutf8__reader__interface) & reader) |
| const [TOML_PURE_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-inline-getter)[source_path_ptr](/libpalliate/generated/Files/source__region_8h#using-source-path-ptr) & | **[source_path](/libpalliate/generated/Classes/classutf8__buffered__reader#function-source-path)**() const |
| const [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[utf8_codepoint](/libpalliate/generated/Classes/structutf8__codepoint) * | **[read_next](/libpalliate/generated/Classes/classutf8__buffered__reader#function-read-next)**() |
| const [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[utf8_codepoint](/libpalliate/generated/Classes/structutf8__codepoint) * | **[step_back](/libpalliate/generated/Classes/classutf8__buffered__reader#function-step-back)**(size_t count) |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) bool | **[peek_eof](/libpalliate/generated/Classes/classutf8__buffered__reader#function-peek-eof)**() const |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) optional< parse_error > && | **[error](/libpalliate/generated/Classes/classutf8__buffered__reader#function-error)**() |

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| constexpr size_t | **[max_history_length](/libpalliate/generated/Classes/classutf8__buffered__reader#variable-max-history-length)**  |
| [utf8_codepoint](/libpalliate/generated/Classes/structutf8__codepoint) | **[buffer](/libpalliate/generated/Classes/classutf8__buffered__reader#variable-buffer)**  |
| size_t | **[count](/libpalliate/generated/Classes/classutf8__buffered__reader#variable-count)**  |
| size_t | **[first](/libpalliate/generated/Classes/classutf8__buffered__reader#variable-first)**  |

## Public Functions Documentation

### function utf8_buffered_reader

```cpp
inline explicit TOML_NODISCARD_CTOR utf8_buffered_reader(
    utf8_reader_interface & reader
)
```


### function source_path

```cpp
inline const TOML_PURE_INLINE_GETTERsource_path_ptr & source_path() const
```


### function read_next

```cpp
inline const TOML_NODISCARDutf8_codepoint * read_next()
```


### function step_back

```cpp
inline const TOML_NODISCARDutf8_codepoint * step_back(
    size_t count
)
```


### function peek_eof

```cpp
inline TOML_NODISCARD bool peek_eof() const
```


### function error

```cpp
inline TOML_NODISCARD optional< parse_error > && error()
```


### function utf8_buffered_reader

```cpp
inline explicit TOML_NODISCARD_CTOR utf8_buffered_reader(
    utf8_reader_interface & reader
)
```


### function source_path

```cpp
inline const TOML_PURE_INLINE_GETTERsource_path_ptr & source_path() const
```


### function read_next

```cpp
inline const TOML_NODISCARDutf8_codepoint * read_next()
```


### function step_back

```cpp
inline const TOML_NODISCARDutf8_codepoint * step_back(
    size_t count
)
```


### function peek_eof

```cpp
inline TOML_NODISCARD bool peek_eof() const
```


### function error

```cpp
inline TOML_NODISCARD optional< parse_error > && error()
```


## Public Attributes Documentation

### variable max_history_length

```cpp
static constexpr size_t max_history_length = 128;
```


### variable buffer

```cpp
utf8_codepoint buffer;
```


### variable count

```cpp
size_t count;
```


### variable first

```cpp
size_t first;
```



_Automatically updated on 2022-05-02 at 01:42:11 +0000._