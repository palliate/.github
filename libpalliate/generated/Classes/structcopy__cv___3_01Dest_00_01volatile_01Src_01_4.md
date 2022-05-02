---
title: copy_cv_< Dest, volatile Src >
parent: Classes
grand_parent: libpalliate
layout: default
---

# copy_cv_< Dest, volatile Src >



 [More...](#detailed-description)


`#include <toml.hpp>`

## Public Types

|                | Name           |
| -------------- | -------------- |
| using std::add_volatile_t< Dest > | **[type](/libpalliate/generated/Classes/structcopy__cv___3_01Dest_00_01volatile_01Src_01_4#using-type)**  |

## Detailed Description

```cpp
template <typename Dest ,
typename Src >
struct copy_cv_< Dest, volatile Src >;
```

## Public Types Documentation

### using type

```cpp
using copy_cv_< Dest, volatile Src >::type =  std::add_volatile_t<Dest>;
```



_Automatically updated on 2022-05-02 at 01:42:07 +0000._