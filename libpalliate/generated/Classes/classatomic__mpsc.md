---
title: atomic_mpsc
parent: Classes
grand_parent: libpalliate
layout: default
---

# atomic_mpsc






`#include <atomic_mpsc.h>`

## Public Classes

|                | Name           |
| -------------- | -------------- |
| struct | **[element](/libpalliate/generated/Classes/structatomic__mpsc_1_1element)**  |

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[atomic_mpsc](/libpalliate/generated/Classes/classatomic__mpsc#function-atomic-mpsc)**(unsigned _size, std::atomic< unsigned > * _freeList, std::atomic< unsigned > * _processList, [element](/libpalliate/generated/Classes/structatomic__mpsc_1_1element) * _list) |
| [element](/libpalliate/generated/Classes/structatomic__mpsc_1_1element) * | **[push](/libpalliate/generated/Classes/classatomic__mpsc#function-push)**(unsigned data) |
| [element](/libpalliate/generated/Classes/structatomic__mpsc_1_1element) * | **[pop](/libpalliate/generated/Classes/classatomic__mpsc#function-pop)**() |
| void | **[clear](/libpalliate/generated/Classes/classatomic__mpsc#function-clear)**([element](/libpalliate/generated/Classes/structatomic__mpsc_1_1element) * e) |
| unsigned | **[get_count](/libpalliate/generated/Classes/classatomic__mpsc#function-get-count)**() |

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| thread_local unsigned | **[tail](/libpalliate/generated/Classes/classatomic__mpsc#variable-tail)**  |

## Public Functions Documentation

### function atomic_mpsc

```cpp
inline atomic_mpsc(
    unsigned _size,
    std::atomic< unsigned > * _freeList,
    std::atomic< unsigned > * _processList,
    element * _list
)
```


### function push

```cpp
inline element * push(
    unsigned data
)
```


### function pop

```cpp
inline element * pop()
```


### function clear

```cpp
inline void clear(
    element * e
)
```


### function get_count

```cpp
inline unsigned get_count()
```


## Public Attributes Documentation

### variable tail

```cpp
static thread_local unsigned tail = 0;
```



_Automatically updated on 2022-05-07 at 23:06:39 +0000._