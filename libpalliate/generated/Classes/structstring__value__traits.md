---
title: string_value_traits
parent: Classes
grand_parent: libpalliate
layout: default
---

# string_value_traits



 [More...](#detailed-description)


`#include <toml.hpp>`

## Public Types

|                | Name           |
| -------------- | -------------- |
| using std::string | **[native_type](/libpalliate/generated/Classes/structstring__value__traits#using-native-type)**  |

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| constexpr bool | **[is_native](/libpalliate/generated/Classes/structstring__value__traits#variable-is-native)**  |
| constexpr bool | **[is_losslessly_convertible_to_native](/libpalliate/generated/Classes/structstring__value__traits#variable-is-losslessly-convertible-to-native)**  |
| constexpr bool | **[can_represent_native](/libpalliate/generated/Classes/structstring__value__traits#variable-can-represent-native)**  |
| constexpr bool | **[can_partially_represent_native](/libpalliate/generated/Classes/structstring__value__traits#variable-can-partially-represent-native)**  |
| constexpr auto | **[type](/libpalliate/generated/Classes/structstring__value__traits#variable-type)**  |

## Detailed Description

```cpp
template <typename T >
struct string_value_traits;
```

## Public Types Documentation

### using native_type

```cpp
using string_value_traits< T >::native_type =  std::string;
```


## Public Attributes Documentation

### variable is_native

```cpp
static constexpr bool is_native = std::is_same_v<T, native_type>;
```


### variable is_losslessly_convertible_to_native

```cpp
static constexpr bool is_losslessly_convertible_to_native = true;
```


### variable can_represent_native

```cpp
static constexpr bool can_represent_native =
			!std::is_array_v<T> && (!std::is_pointer_v<T> || std::is_const_v<std::remove_pointer_t<T>>);
```


### variable can_partially_represent_native

```cpp
static constexpr bool can_partially_represent_native = can_represent_native;
```


### variable type

```cpp
static constexpr auto type = node_type::string;
```



_Automatically updated on 2022-05-02 at 01:42:07 +0000._