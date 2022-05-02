---
title: atomic_cr::element
parent: Classes
grand_parent: libpalliate
layout: default
---

# atomic_cr::element






`#include <atomic_cr.h>`

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[element](/libpalliate/generated/Classes/classatomic__cr_1_1element#function-element)**() =default |
| | **[element](/libpalliate/generated/Classes/classatomic__cr_1_1element#function-element)**(unsigned char * memory) |
| void | **[respond](/libpalliate/generated/Classes/classatomic__cr_1_1element#function-respond)**([response_t](/libpalliate/generated/Classes/classatomic__cr#using-response-t) value) |
| void | **[finish](/libpalliate/generated/Classes/classatomic__cr_1_1element#function-finish)**() |

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| std::atomic< [request_t](/libpalliate/generated/Classes/classatomic__cr#using-request-t) > * | **[req](/libpalliate/generated/Classes/classatomic__cr_1_1element#variable-req)**  |
| std::atomic< [response_t](/libpalliate/generated/Classes/classatomic__cr#using-response-t) > * | **[resp](/libpalliate/generated/Classes/classatomic__cr_1_1element#variable-resp)**  |

## Friends

|                | Name           |
| -------------- | -------------- |
| class | **[atomic_cr](/libpalliate/generated/Classes/classatomic__cr_1_1element#friend-atomic-cr)**  |

## Public Functions Documentation

### function element

```cpp
element() =default
```


### function element

```cpp
inline explicit element(
    unsigned char * memory
)
```


### function respond

```cpp
inline void respond(
    response_t value
)
```


### function finish

```cpp
inline void finish()
```


## Public Attributes Documentation

### variable req

```cpp
std::atomic< request_t > * req = nullptr;
```


### variable resp

```cpp
std::atomic< response_t > * resp = nullptr;
```


## Friends

### friend atomic_cr

```cpp
friend class atomic_cr;
```



_Automatically updated on 2022-05-02 at 01:42:07 +0000._