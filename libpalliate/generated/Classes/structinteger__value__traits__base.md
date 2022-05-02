---
title: integer_value_traits_base
parent: Classes
grand_parent: libpalliate
layout: default
---

# integer_value_traits_base



 [More...](#detailed-description)


`#include <toml.hpp>`

Inherits from [integer_value_limits< T >](/libpalliate/generated/Classes/structinteger__value__limits)

Inherited by [signed_integer_value_traits< T >](/libpalliate/generated/Classes/structsigned__integer__value__traits), [unsigned_integer_value_traits< T >](/libpalliate/generated/Classes/structunsigned__integer__value__traits)

## Public Types

|                | Name           |
| -------------- | -------------- |
| using int64_t | **[native_type](/libpalliate/generated/Classes/structinteger__value__traits__base#using-native-type)**  |

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| constexpr bool | **[is_native](/libpalliate/generated/Classes/structinteger__value__traits__base#variable-is-native)**  |
| constexpr bool | **[is_signed](/libpalliate/generated/Classes/structinteger__value__traits__base#variable-is-signed)**  |
| constexpr auto | **[type](/libpalliate/generated/Classes/structinteger__value__traits__base#variable-type)**  |
| constexpr bool | **[can_partially_represent_native](/libpalliate/generated/Classes/structinteger__value__traits__base#variable-can-partially-represent-native)**  |

## Additional inherited members

**Public Attributes inherited from [integer_value_limits< T >](/libpalliate/generated/Classes/structinteger__value__limits)**

|                | Name           |
| -------------- | -------------- |
| constexpr auto | **[min](/libpalliate/generated/Classes/structinteger__value__limits#variable-min)**  |
| constexpr auto | **[max](/libpalliate/generated/Classes/structinteger__value__limits#variable-max)**  |


## Detailed Description

```cpp
template <typename T >
struct integer_value_traits_base;
```

## Public Types Documentation

### using native_type

```cpp
using integer_value_traits_base< T >::native_type =  int64_t;
```


## Public Attributes Documentation

### variable is_native

```cpp
static constexpr bool is_native = std::is_same_v<T, native_type>;
```


### variable is_signed

```cpp
static constexpr bool is_signed = static_cast<T>(-1) < T{};
```


### variable type

```cpp
static constexpr auto type = node_type::integer;
```


### variable can_partially_represent_native

```cpp
static constexpr bool can_partially_represent_native = true;
```



_Automatically updated on 2022-05-02 at 01:42:07 +0000._