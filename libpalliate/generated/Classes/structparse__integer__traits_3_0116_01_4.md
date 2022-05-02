---
title: parse_integer_traits< 16 >
parent: Classes
grand_parent: libpalliate
layout: default
---

# parse_integer_traits< 16 >






`#include <toml.hpp>`

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| constexpr auto | **[scope_qualifier](/libpalliate/generated/Classes/structparse__integer__traits_3_0116_01_4#variable-scope-qualifier)**  |
| constexpr auto | **[is_digit](/libpalliate/generated/Classes/structparse__integer__traits_3_0116_01_4#variable-is-digit)**  |
| constexpr auto | **[is_signed](/libpalliate/generated/Classes/structparse__integer__traits_3_0116_01_4#variable-is-signed)**  |
| constexpr auto | **[max_digits](/libpalliate/generated/Classes/structparse__integer__traits_3_0116_01_4#variable-max-digits)**  |
| constexpr auto | **[prefix_codepoint](/libpalliate/generated/Classes/structparse__integer__traits_3_0116_01_4#variable-prefix-codepoint)**  |
| constexpr auto | **[prefix](/libpalliate/generated/Classes/structparse__integer__traits_3_0116_01_4#variable-prefix)**  |
| constexpr auto | **[full_prefix](/libpalliate/generated/Classes/structparse__integer__traits_3_0116_01_4#variable-full-prefix)**  |

## Public Attributes Documentation

### variable scope_qualifier

```cpp
static constexpr auto scope_qualifier = "hexadecimal integer"sv;
```


### variable is_digit

```cpp
static constexpr auto is_digit = impl::is_hexadecimal_digit;
```


### variable is_signed

```cpp
static constexpr auto is_signed = false;
```


### variable max_digits

```cpp
static constexpr auto max_digits = 16;
```


### variable prefix_codepoint

```cpp
static constexpr auto prefix_codepoint = U'x';
```


### variable prefix

```cpp
static constexpr auto prefix = "x"sv;
```


### variable full_prefix

```cpp
static constexpr auto full_prefix = "0x"sv;
```



_Automatically updated on 2022-05-02 at 01:42:11 +0000._