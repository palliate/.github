---
title: atomic_cr::element

---

# atomic_cr::element






`#include <atomic_cr.h>`

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[element](Classes/classatomic__cr_1_1element.md#function-element)**() =default |
| | **[element](Classes/classatomic__cr_1_1element.md#function-element)**(unsigned char * memory) |
| void | **[respond](Classes/classatomic__cr_1_1element.md#function-respond)**([response_t](Classes/classatomic__cr.md#using-response-t) value) |
| void | **[finish](Classes/classatomic__cr_1_1element.md#function-finish)**() |

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| std::atomic< [request_t](Classes/classatomic__cr.md#using-request-t) > * | **[req](Classes/classatomic__cr_1_1element.md#variable-req)**  |
| std::atomic< [response_t](Classes/classatomic__cr.md#using-response-t) > * | **[resp](Classes/classatomic__cr_1_1element.md#variable-resp)**  |

## Friends

|                | Name           |
| -------------- | -------------- |
| class | **[atomic_cr](Classes/classatomic__cr_1_1element.md#friend-atomic-cr)**  |

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


-------------------------------

Updated on 2022-04-30 at 06:56:37 +0000