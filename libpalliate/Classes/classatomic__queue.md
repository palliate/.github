---
title: atomic_queue

---

# atomic_queue






`#include <atomic_queue.h>`

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[atomic_queue](Classes/classatomic__queue.md#function-atomic-queue)**(char _size, std::atomic< unsigned char > * _head, std::atomic< unsigned char > * _tail, int * _list) |
| | **[~atomic_queue](Classes/classatomic__queue.md#function-~atomic-queue)**() |
| template <bool overwrite =false,unsigned sleep_time =50,bool count_missed =false\> <br>void | **[push](Classes/classatomic__queue.md#function-push)**(int value) |
| template <bool block =true,unsigned sleep_time =50\> <br>int | **[pop](Classes/classatomic__queue.md#function-pop)**() |

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| unsigned | **[missed](Classes/classatomic__queue.md#variable-missed)**  |

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


-------------------------------

Updated on 2022-04-30 at 06:56:37 +0000