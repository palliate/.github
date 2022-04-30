---
title: atomic_reqresp

---

# atomic_reqresp






`#include <atomic_reqresp.h>`

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[atomic_reqresp](Classes/classatomic__reqresp.md#function-atomic-reqresp)**(char _size, std::atomic_char * _writePos, void * _list) |
| void | **[push](Classes/classatomic__reqresp.md#function-push)**(int value) |
| template <bool waitForResponse =false\> <br>[element](Classes/structelement.md) * | **[pop](Classes/classatomic__reqresp.md#function-pop)**() |

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| unsigned | **[missed](Classes/classatomic__reqresp.md#variable-missed)**  |
| unsigned char | **[readPos](Classes/classatomic__reqresp.md#variable-readpos)**  |

## Public Functions Documentation

### function atomic_reqresp

```cpp
inline atomic_reqresp(
    char _size,
    std::atomic_char * _writePos,
    void * _list
)
```


### function push

```cpp
inline void push(
    int value
)
```


### function pop

```cpp
template <bool waitForResponse =false>
inline element * pop()
```


## Public Attributes Documentation

### variable missed

```cpp
unsigned missed = 0;
```


### variable readPos

```cpp
unsigned char readPos = 0;
```


-------------------------------

Updated on 2022-04-30 at 06:56:37 +0000