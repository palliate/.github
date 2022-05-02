---
title: node_wrapper< const T >
parent: Classes
grand_parent: libpalliate
layout: default
---

# node_wrapper< const T >



 [More...](#detailed-description)


`#include <toml.hpp>`

## Public Types

|                | Name           |
| -------------- | -------------- |
| using std::add_const_t< typename [node_wrapper](/libpalliate/generated/Classes/structnode__wrapper)< T >::[type](/libpalliate/generated/Classes/structnode__wrapper_3_01const_01T_01_4#using-type) > | **[type](/libpalliate/generated/Classes/structnode__wrapper_3_01const_01T_01_4#using-type)**  |

## Detailed Description

```cpp
template <typename T >
struct node_wrapper< const T >;
```

## Public Types Documentation

### using type

```cpp
using node_wrapper< const T >::type =  std::add_const_t<typename node_wrapper<T>::type>;
```



_Automatically updated on 2022-05-02 at 01:42:11 +0000._