---
title: mpsc

---

# mpsc



 [More...](#detailed-description)


`#include <mpsc.h>`

## Public Classes

|                | Name           |
| -------------- | -------------- |
| struct | **[element_t](Classes/structmpsc_1_1element__t.md)**  |

## Public Functions

|                | Name           |
| -------------- | -------------- |
| void | **[push](Classes/classmpsc.md#function-push)**(T value) |
| [element_t](Classes/structmpsc_1_1element__t.md) & | **[pop](Classes/classmpsc.md#function-pop)**() |
| void | **[finish](Classes/classmpsc.md#function-finish)**([element_t](Classes/structmpsc_1_1element__t.md) & element) |

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


-------------------------------

Updated on 2022-04-30 at 06:56:37 +0000