---
title: node_unwrapper< const volatile value< T > >
parent: Classes
grand_parent: libpalliate
layout: default
---

# node_unwrapper< const volatile value< T > >



 [More...](#detailed-description)


`#include <toml.hpp>`

## Public Types

|                | Name           |
| -------------- | -------------- |
| using std::add_volatile_t< std::add_const_t< T > > | **[type](/libpalliate/generated/Classes/structnode__unwrapper_3_01const_01volatile_01value_3_01T_01_4_01_4#using-type)**  |

## Detailed Description

```cpp
template <typename T >
struct node_unwrapper< const volatile value< T > >;
```

## Public Types Documentation

### using type

```cpp
using node_unwrapper< const volatile value< T > >::type =  std::add_volatile_t<std::add_const_t<T> >;
```



_Automatically updated on 2022-05-02 at 01:42:11 +0000._