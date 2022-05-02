---
title: atomic_semaphore
parent: Classes
grand_parent: libpalliate
layout: default
---

# atomic_semaphore






`#include <atomic_semaphore.h>`

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[atomic_semaphore](/libpalliate/generated/Classes/classatomic__semaphore#function-atomic-semaphore)**(char _size, std::atomic< unsigned char > * _write, std::atomic< unsigned char > * _readers, void * _list) |
| template <bool overwrite =false,unsigned sleep_time =50,bool count_missed =false\> <br>void | **[push](/libpalliate/generated/Classes/classatomic__semaphore#function-push)**(int value) |
| template <bool block =true,unsigned sleep_time =50\> <br>int | **[pop](/libpalliate/generated/Classes/classatomic__semaphore#function-pop)**() |
| void | **[add_reader](/libpalliate/generated/Classes/classatomic__semaphore#function-add-reader)**() |
| void | **[remove_reader](/libpalliate/generated/Classes/classatomic__semaphore#function-remove-reader)**() |

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| unsigned | **[missed](/libpalliate/generated/Classes/classatomic__semaphore#variable-missed)**  |
| thread_local unsigned char | **[readPos](/libpalliate/generated/Classes/classatomic__semaphore#variable-readpos)**  |

## Public Functions Documentation

### function atomic_semaphore

```cpp
inline explicit atomic_semaphore(
    char _size,
    std::atomic< unsigned char > * _write,
    std::atomic< unsigned char > * _readers,
    void * _list
)
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


### function add_reader

```cpp
void add_reader()
```


### function remove_reader

```cpp
void remove_reader()
```


## Public Attributes Documentation

### variable missed

```cpp
unsigned missed = 0;
```


### variable readPos

```cpp
static thread_local unsigned char readPos = 0;
```



_Automatically updated on 2022-05-02 at 01:42:11 +0000._