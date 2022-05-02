---
title: float_value_limits
parent: Classes
grand_parent: libpalliate
layout: default
---

# float_value_limits



 [More...](#detailed-description)


`#include <toml.hpp>`

Inherited by [float_value_traits< T >](/libpalliate/generated/Classes/structfloat__value__traits)

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| constexpr bool | **[is_iec559](/libpalliate/generated/Classes/structfloat__value__limits#variable-is-iec559)**  |
| constexpr int | **[digits](/libpalliate/generated/Classes/structfloat__value__limits#variable-digits)**  |
| constexpr int | **[digits10](/libpalliate/generated/Classes/structfloat__value__limits#variable-digits10)**  |

## Detailed Description

```cpp
template <typename T >
struct float_value_limits;
```

## Public Attributes Documentation

### variable is_iec559

```cpp
static constexpr bool is_iec559 = std::numeric_limits<T>::is_iec559;
```


### variable digits

```cpp
static constexpr int digits = std::numeric_limits<T>::digits;
```


### variable digits10

```cpp
static constexpr int digits10 = std::numeric_limits<T>::digits10;
```



_Automatically updated on 2022-05-02 at 01:42:07 +0000._