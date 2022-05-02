---
title: float_value_traits
parent: Classes
grand_parent: libpalliate
layout: default
---

# float_value_traits



 [More...](#detailed-description)


`#include <toml.hpp>`

Inherits from [float_value_limits< T >](/libpalliate/generated/Classes/structfloat__value__limits)

## Public Types

|                | Name           |
| -------------- | -------------- |
| using double | **[native_type](/libpalliate/generated/Classes/structfloat__value__traits#using-native-type)**  |

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| constexpr bool | **[is_native](/libpalliate/generated/Classes/structfloat__value__traits#variable-is-native)**  |
| constexpr bool | **[is_signed](/libpalliate/generated/Classes/structfloat__value__traits#variable-is-signed)**  |
| constexpr bool | **[is_losslessly_convertible_to_native](/libpalliate/generated/Classes/structfloat__value__traits#variable-is-losslessly-convertible-to-native)**  |
| constexpr bool | **[can_represent_native](/libpalliate/generated/Classes/structfloat__value__traits#variable-can-represent-native)**  |
| constexpr bool | **[can_partially_represent_native](/libpalliate/generated/Classes/structfloat__value__traits#variable-can-partially-represent-native)**  |
| constexpr auto | **[type](/libpalliate/generated/Classes/structfloat__value__traits#variable-type)**  |

## Additional inherited members

**Public Attributes inherited from [float_value_limits< T >](/libpalliate/generated/Classes/structfloat__value__limits)**

|                | Name           |
| -------------- | -------------- |
| constexpr bool | **[is_iec559](/libpalliate/generated/Classes/structfloat__value__limits#variable-is-iec559)**  |
| constexpr int | **[digits](/libpalliate/generated/Classes/structfloat__value__limits#variable-digits)**  |
| constexpr int | **[digits10](/libpalliate/generated/Classes/structfloat__value__limits#variable-digits10)**  |


## Detailed Description

```cpp
template <typename T >
struct float_value_traits;
```

## Public Types Documentation

### using native_type

```cpp
using float_value_traits< T >::native_type =  double;
```


## Public Attributes Documentation

### variable is_native

```cpp
static constexpr bool is_native = std::is_same_v<T, native_type>;
```


### variable is_signed

```cpp
static constexpr bool is_signed = true;
```


### variable is_losslessly_convertible_to_native

```cpp
static constexpr bool is_losslessly_convertible_to_native = float_value_limits<T>::is_iec559
																 && float_value_limits<T>::digits <= 53
																 && float_value_limits<T>::digits10 <= 15;
```


### variable can_represent_native

```cpp
static constexpr bool can_represent_native = float_value_limits<T>::is_iec559
												  && float_value_limits<T>::digits >= 53	
												  && float_value_limits<T>::digits10 >= 15;
```


### variable can_partially_represent_native

```cpp
static constexpr bool can_partially_represent_native = float_value_limits<T>::is_iec559				 
		   && float_value_limits<T>::digits >= 24			 
		   && float_value_limits<T>::digits10 >= 6;
```


### variable type

```cpp
static constexpr auto type = node_type::floating_point;
```



_Automatically updated on 2022-05-02 at 01:42:11 +0000._