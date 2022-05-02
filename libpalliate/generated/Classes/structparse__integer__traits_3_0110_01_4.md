---
title: parse_integer_traits< 10 >
parent: Classes
grand_parent: libpalliate
layout: default
---

# parse_integer_traits< 10 >






`#include <toml.hpp>`

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| constexpr auto | **[scope_qualifier](/libpalliate/generated/Classes/structparse__integer__traits_3_0110_01_4#variable-scope-qualifier)**  |
| constexpr auto | **[is_digit](/libpalliate/generated/Classes/structparse__integer__traits_3_0110_01_4#variable-is-digit)**  |
| constexpr auto | **[is_signed](/libpalliate/generated/Classes/structparse__integer__traits_3_0110_01_4#variable-is-signed)**  |
| constexpr auto | **[max_digits](/libpalliate/generated/Classes/structparse__integer__traits_3_0110_01_4#variable-max-digits)**  |
| constexpr auto | **[full_prefix](/libpalliate/generated/Classes/structparse__integer__traits_3_0110_01_4#variable-full-prefix)**  |

## Public Attributes Documentation

### variable scope_qualifier

```cpp
static constexpr auto scope_qualifier = "decimal integer"sv;
```


### variable is_digit

```cpp
static constexpr auto is_digit = impl::is_decimal_digit;
```


### variable is_signed

```cpp
static constexpr auto is_signed = true;
```


### variable max_digits

```cpp
static constexpr auto max_digits = 19;
```


### variable full_prefix

```cpp
static constexpr auto full_prefix = ""sv;
```



_Automatically updated on 2022-05-02 at 01:42:11 +0000._