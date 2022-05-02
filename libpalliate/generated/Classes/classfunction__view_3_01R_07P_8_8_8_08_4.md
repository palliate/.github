---
title: function_view< R(P...)>
parent: Classes
grand_parent: libpalliate
layout: default
---

# function_view< R(P...)>



 [More...](#detailed-description)


`#include <tests.h>`

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[function_view](/libpalliate/generated/Classes/classfunction__view_3_01R_07P_8_8_8_08_4#function-function-view)**() =default |
| template <typename T \> <br>| **[function_view](/libpalliate/generated/Classes/classfunction__view_3_01R_07P_8_8_8_08_4#function-function-view)**(T && x) |
| decltype(auto) | **[operator()](/libpalliate/generated/Classes/classfunction__view_3_01R_07P_8_8_8_08_4#function-operator())**(P &&... xs) const |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) | **[operator bool](/libpalliate/generated/Classes/classfunction__view_3_01R_07P_8_8_8_08_4#function-operator-bool)**() const |

## Detailed Description

```cpp
template <typename R ,
typename... P>
class function_view< R(P...)>;
```

## Public Functions Documentation

### function function_view

```cpp
function_view() =default
```


### function function_view

```cpp
template <typename T >
inline function_view(
    T && x
)
```


### function operator()

```cpp
inline decltype(auto) operator()(
    P &&... xs
) const
```


### function operator bool

```cpp
inline TOML_NODISCARD operator bool() const
```



_Automatically updated on 2022-05-02 at 01:42:07 +0000._