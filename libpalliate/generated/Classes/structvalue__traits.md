---
title: value_traits
parent: Classes
grand_parent: libpalliate
layout: default
---

# value_traits



 [More...](#detailed-description)


`#include <toml.hpp>`

Inherited by [value_traits< const T >](/libpalliate/generated/Classes/structvalue__traits_3_01const_01T_01_4), [value_traits< const volatile T >](/libpalliate/generated/Classes/structvalue__traits_3_01const_01volatile_01T_01_4), [value_traits< T & >](/libpalliate/generated/Classes/structvalue__traits_3_01T_01_6_01_4), [value_traits< T && >](/libpalliate/generated/Classes/structvalue__traits_3_01T_01_6_6_01_4), [value_traits< volatile T >](/libpalliate/generated/Classes/structvalue__traits_3_01volatile_01T_01_4)

## Public Types

|                | Name           |
| -------------- | -------------- |
| using void | **[native_type](/libpalliate/generated/Classes/structvalue__traits#using-native-type)**  |

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| constexpr bool | **[is_native](/libpalliate/generated/Classes/structvalue__traits#variable-is-native)**  |
| constexpr bool | **[is_losslessly_convertible_to_native](/libpalliate/generated/Classes/structvalue__traits#variable-is-losslessly-convertible-to-native)**  |
| constexpr bool | **[can_represent_native](/libpalliate/generated/Classes/structvalue__traits#variable-can-represent-native)**  |
| constexpr bool | **[can_partially_represent_native](/libpalliate/generated/Classes/structvalue__traits#variable-can-partially-represent-native)**  |
| constexpr auto | **[type](/libpalliate/generated/Classes/structvalue__traits#variable-type)**  |

## Detailed Description

```cpp
template <typename T >
struct value_traits;
```

## Public Types Documentation

### using native_type

```cpp
using value_traits< T >::native_type =  void;
```


## Public Attributes Documentation

### variable is_native

```cpp
static constexpr bool is_native = false;
```


### variable is_losslessly_convertible_to_native

```cpp
static constexpr bool is_losslessly_convertible_to_native = false;
```


### variable can_represent_native

```cpp
static constexpr bool can_represent_native = false;
```


### variable can_partially_represent_native

```cpp
static constexpr bool can_partially_represent_native = false;
```


### variable type

```cpp
static constexpr auto type = node_type::none;
```



_Automatically updated on 2022-05-02 at 01:42:11 +0000._