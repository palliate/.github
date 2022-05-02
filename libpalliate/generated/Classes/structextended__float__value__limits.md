---
title: extended_float_value_limits
parent: Classes
grand_parent: libpalliate
layout: default
---

# extended_float_value_limits



 [More...](#detailed-description)


`#include <toml.hpp>`

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| constexpr bool | **[is_iec559](/libpalliate/generated/Classes/structextended__float__value__limits#variable-is-iec559)**  |
| constexpr int | **[digits](/libpalliate/generated/Classes/structextended__float__value__limits#variable-digits)**  |
| constexpr int | **[digits10](/libpalliate/generated/Classes/structextended__float__value__limits#variable-digits10)**  |

## Detailed Description

```cpp
template <int mant_dig,
int dig>
struct extended_float_value_limits;
```

## Public Attributes Documentation

### variable is_iec559

```cpp
static constexpr bool is_iec559 = true;
```


### variable digits

```cpp
static constexpr int digits = mant_dig;
```


### variable digits10

```cpp
static constexpr int digits10 = dig;
```



_Automatically updated on 2022-05-02 at 01:42:07 +0000._