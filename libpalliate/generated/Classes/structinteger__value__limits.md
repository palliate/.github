---
title: integer_value_limits
parent: Classes
grand_parent: libpalliate
layout: default
---

# integer_value_limits



 [More...](#detailed-description)


`#include <toml.hpp>`

Inherited by [integer_value_traits_base< T >](/libpalliate/generated/Classes/structinteger__value__traits__base)

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| constexpr auto | **[min](/libpalliate/generated/Classes/structinteger__value__limits#variable-min)**  |
| constexpr auto | **[max](/libpalliate/generated/Classes/structinteger__value__limits#variable-max)**  |

## Detailed Description

```cpp
template <typename T >
struct integer_value_limits;
```

## Public Attributes Documentation

### variable min

```cpp
static constexpr auto min = (std::numeric_limits<T>::min)();
```


### variable max

```cpp
static constexpr auto max = (std::numeric_limits<T>::max)();
```



_Automatically updated on 2022-05-02 at 01:42:11 +0000._