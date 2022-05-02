---
title: mpsc
parent: Classes
grand_parent: libpalliate
layout: default
---

# mpsc



 [More...](#detailed-description)


`#include <mpsc.h>`

## Public Classes

|                | Name           |
| -------------- | -------------- |
| struct | **[element_t](/libpalliate/generated/Classes/structmpsc_1_1element__t)**  |

## Public Functions

|                | Name           |
| -------------- | -------------- |
| void | **[push](/libpalliate/generated/Classes/classmpsc#function-push)**(T value) |
| [element_t](/libpalliate/generated/Classes/structmpsc_1_1element__t) & | **[pop](/libpalliate/generated/Classes/classmpsc#function-pop)**() |
| void | **[finish](/libpalliate/generated/Classes/classmpsc#function-finish)**([element_t](/libpalliate/generated/Classes/structmpsc_1_1element__t) & element) |

## Detailed Description

```cpp
template <typename T ,
unsigned size>
class mpsc;
```

## Public Functions Documentation

### function push

```cpp
inline void push(
    T value
)
```


### function pop

```cpp
inline element_t & pop()
```


### function finish

```cpp
inline void finish(
    element_t & element
)
```



_Automatically updated on 2022-05-02 at 01:42:07 +0000._