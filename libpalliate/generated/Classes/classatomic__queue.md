---
title: atomic_queue
parent: Classes
grand_parent: libpalliate
layout: default
---

# atomic_queue






`#include <atomic_queue.h>`

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[atomic_queue](/libpalliate/generated/Classes/classatomic__queue#function-atomic-queue)**(char _size, std::atomic< unsigned char > * _head, std::atomic< unsigned char > * _tail, int * _list) |
| | **[~atomic_queue](/libpalliate/generated/Classes/classatomic__queue#function-~atomic-queue)**() |
| template <bool overwrite =false,unsigned sleep_time =50,bool count_missed =false\> <br>void | **[push](/libpalliate/generated/Classes/classatomic__queue#function-push)**(int value) |
| template <bool block =true,unsigned sleep_time =50\> <br>int | **[pop](/libpalliate/generated/Classes/classatomic__queue#function-pop)**() |

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| unsigned | **[missed](/libpalliate/generated/Classes/classatomic__queue#variable-missed)**  |

## Public Functions Documentation

### function atomic_queue

```cpp
inline atomic_queue(
    char _size,
    std::atomic< unsigned char > * _head,
    std::atomic< unsigned char > * _tail,
    int * _list
)
```


### function ~atomic_queue

```cpp
~atomic_queue()
```


### function push

```cpp
template <bool overwrite =false,
unsigned sleep_time =50,
bool count_missed =false>
inline void push(
    int value
)
```


### function pop

```cpp
template <bool block =true,
unsigned sleep_time =50>
inline int pop()
```


## Public Attributes Documentation

### variable missed

```cpp
unsigned missed = 0;
```



_Automatically updated on 2022-05-07 at 23:06:39 +0000._