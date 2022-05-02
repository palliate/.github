---
title: atomic_reqresp
parent: Classes
grand_parent: libpalliate
layout: default
---

# atomic_reqresp






`#include <atomic_reqresp.h>`

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[atomic_reqresp](/libpalliate/generated/Classes/classatomic__reqresp#function-atomic-reqresp)**(char _size, std::atomic_char * _writePos, void * _list) |
| void | **[push](/libpalliate/generated/Classes/classatomic__reqresp#function-push)**(int value) |
| template <bool waitForResponse =false\> <br>[element](/libpalliate/generated/Classes/structelement) * | **[pop](/libpalliate/generated/Classes/classatomic__reqresp#function-pop)**() |

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| unsigned | **[missed](/libpalliate/generated/Classes/classatomic__reqresp#variable-missed)**  |
| unsigned char | **[readPos](/libpalliate/generated/Classes/classatomic__reqresp#variable-readpos)**  |

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



_Automatically updated on 2022-05-02 at 01:49:10 +0000._