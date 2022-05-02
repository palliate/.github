---
title: copy_ref_< Dest, Src & >
parent: Classes
grand_parent: libpalliate
layout: default
---

# copy_ref_< Dest, Src & >



 [More...](#detailed-description)


`#include <toml.hpp>`

## Public Types

|                | Name           |
| -------------- | -------------- |
| using std::add_lvalue_reference_t< Dest > | **[type](/libpalliate/generated/Classes/structcopy__ref___3_01Dest_00_01Src_01_6_01_4#using-type)**  |

## Detailed Description

```cpp
template <typename Dest ,
typename Src >
struct copy_ref_< Dest, Src & >;
```

## Public Types Documentation

### using type

```cpp
using copy_ref_< Dest, Src & >::type =  std::add_lvalue_reference_t<Dest>;
```



_Automatically updated on 2022-05-02 at 01:42:07 +0000._