---
title: atomic_semaphore

---

# atomic_semaphore






`#include <atomic_semaphore.h>`

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[atomic_semaphore](Classes/classatomic__semaphore.md#function-atomic-semaphore)**(char _size, std::atomic< unsigned char > * _write, std::atomic< unsigned char > * _readers, void * _list) |
| template <bool overwrite =false,unsigned sleep_time =50,bool count_missed =false\> <br>void | **[push](Classes/classatomic__semaphore.md#function-push)**(int value) |
| template <bool block =true,unsigned sleep_time =50\> <br>int | **[pop](Classes/classatomic__semaphore.md#function-pop)**() |
| void | **[add_reader](Classes/classatomic__semaphore.md#function-add-reader)**() |
| void | **[remove_reader](Classes/classatomic__semaphore.md#function-remove-reader)**() |

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| unsigned | **[missed](Classes/classatomic__semaphore.md#variable-missed)**  |
| thread_local unsigned char | **[readPos](Classes/classatomic__semaphore.md#variable-readpos)**  |

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


-------------------------------

Updated on 2022-04-30 at 06:56:37 +0000