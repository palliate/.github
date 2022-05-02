---
title: parse_key_buffer
parent: Classes
grand_parent: libpalliate
layout: default
---

# parse_key_buffer






`#include <toml.hpp>`

## Public Functions

|                | Name           |
| -------------- | -------------- |
| void | **[clear](/libpalliate/generated/Classes/structparse__key__buffer#function-clear)**() |
| void | **[push_back](/libpalliate/generated/Classes/structparse__key__buffer#function-push-back)**(std::string_view segment, [source_position](/libpalliate/generated/Classes/structsource__position) b, [source_position](/libpalliate/generated/Classes/structsource__position) e) |
| [TOML_PURE_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-inline-getter) std::string_view | **[operator[]](/libpalliate/generated/Classes/structparse__key__buffer#function-operator[])**(size_t i) const |
| [TOML_PURE_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-inline-getter) std::string_view | **[back](/libpalliate/generated/Classes/structparse__key__buffer#function-back)**() const |
| [TOML_PURE_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-inline-getter) bool | **[empty](/libpalliate/generated/Classes/structparse__key__buffer#function-empty)**() const |
| [TOML_PURE_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-inline-getter) size_t | **[size](/libpalliate/generated/Classes/structparse__key__buffer#function-size)**() const |
| void | **[clear](/libpalliate/generated/Classes/structparse__key__buffer#function-clear)**() |
| void | **[push_back](/libpalliate/generated/Classes/structparse__key__buffer#function-push-back)**(std::string_view segment, [source_position](/libpalliate/generated/Classes/structsource__position) b, [source_position](/libpalliate/generated/Classes/structsource__position) e) |
| [TOML_PURE_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-inline-getter) std::string_view | **[operator[]](/libpalliate/generated/Classes/structparse__key__buffer#function-operator[])**(size_t i) const |
| [TOML_PURE_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-inline-getter) std::string_view | **[back](/libpalliate/generated/Classes/structparse__key__buffer#function-back)**() const |
| [TOML_PURE_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-inline-getter) bool | **[empty](/libpalliate/generated/Classes/structparse__key__buffer#function-empty)**() const |
| [TOML_PURE_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-inline-getter) size_t | **[size](/libpalliate/generated/Classes/structparse__key__buffer#function-size)**() const |

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| std::string | **[buffer](/libpalliate/generated/Classes/structparse__key__buffer#variable-buffer)**  |
| std::vector< std::pair< size_t, size_t > > | **[segments](/libpalliate/generated/Classes/structparse__key__buffer#variable-segments)**  |
| std::vector< [source_position](/libpalliate/generated/Classes/structsource__position) > | **[starts](/libpalliate/generated/Classes/structparse__key__buffer#variable-starts)**  |
| std::vector< [source_position](/libpalliate/generated/Classes/structsource__position) > | **[ends](/libpalliate/generated/Classes/structparse__key__buffer#variable-ends)**  |

## Public Functions Documentation

### function clear

```cpp
inline void clear()
```


### function push_back

```cpp
inline void push_back(
    std::string_view segment,
    source_position b,
    source_position e
)
```


### function operator[]

```cpp
inline TOML_PURE_INLINE_GETTER std::string_view operator[](
    size_t i
) const
```


### function back

```cpp
inline TOML_PURE_INLINE_GETTER std::string_view back() const
```


### function empty

```cpp
inline TOML_PURE_INLINE_GETTER bool empty() const
```


### function size

```cpp
inline TOML_PURE_INLINE_GETTER size_t size() const
```


### function clear

```cpp
inline void clear()
```


### function push_back

```cpp
inline void push_back(
    std::string_view segment,
    source_position b,
    source_position e
)
```


### function operator[]

```cpp
inline TOML_PURE_INLINE_GETTER std::string_view operator[](
    size_t i
) const
```


### function back

```cpp
inline TOML_PURE_INLINE_GETTER std::string_view back() const
```


### function empty

```cpp
inline TOML_PURE_INLINE_GETTER bool empty() const
```


### function size

```cpp
inline TOML_PURE_INLINE_GETTER size_t size() const
```


## Public Attributes Documentation

### variable buffer

```cpp
std::string buffer;
```


### variable segments

```cpp
std::vector< std::pair< size_t, size_t > > segments;
```


### variable starts

```cpp
std::vector< source_position > starts;
```


### variable ends

```cpp
std::vector< source_position > ends;
```



_Automatically updated on 2022-05-02 at 01:42:07 +0000._