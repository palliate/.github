---
title: native_value_traits
parent: Classes
grand_parent: libpalliate
layout: default
---

# native_value_traits



 [More...](#detailed-description)


`#include <toml.hpp>`

## Public Types

|                | Name           |
| -------------- | -------------- |
| using T | **[native_type](/libpalliate/generated/Classes/structnative__value__traits#using-native-type)**  |

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| constexpr bool | **[is_native](/libpalliate/generated/Classes/structnative__value__traits#variable-is-native)**  |
| constexpr bool | **[is_losslessly_convertible_to_native](/libpalliate/generated/Classes/structnative__value__traits#variable-is-losslessly-convertible-to-native)**  |
| constexpr bool | **[can_represent_native](/libpalliate/generated/Classes/structnative__value__traits#variable-can-represent-native)**  |
| constexpr bool | **[can_partially_represent_native](/libpalliate/generated/Classes/structnative__value__traits#variable-can-partially-represent-native)**  |
| constexpr auto | **[type](/libpalliate/generated/Classes/structnative__value__traits#variable-type)**  |

## Detailed Description

```cpp
template <typename T ,
node_type NodeType>
struct native_value_traits;
```

## Public Types Documentation

### using native_type

```cpp
using native_value_traits< T, NodeType >::native_type =  T;
```


## Public Attributes Documentation

### variable is_native

```cpp
static constexpr bool is_native = true;
```


### variable is_losslessly_convertible_to_native

```cpp
static constexpr bool is_losslessly_convertible_to_native = true;
```


### variable can_represent_native

```cpp
static constexpr bool can_represent_native = true;
```


### variable can_partially_represent_native

```cpp
static constexpr bool can_partially_represent_native = true;
```


### variable type

```cpp
static constexpr auto type = NodeType;
```



_Automatically updated on 2022-05-02 at 01:42:07 +0000._