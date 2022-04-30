---
title: atomic_cr

---

# atomic_cr



 [More...](#detailed-description)


`#include <atomic_cr.h>`

## Public Classes

|                | Name           |
| -------------- | -------------- |
| class | **[element](Classes/classatomic__cr_1_1element.md)**  |

## Public Types

|                | Name           |
| -------------- | -------------- |
| enum unsigned | **[@0](Classes/classatomic__cr.md#enum-@0)** { UNUSED = 0ul} |
| using unsigned | **[request_t](Classes/classatomic__cr.md#using-request-t)**  |
| using unsigned | **[response_t](Classes/classatomic__cr.md#using-response-t)**  |

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[atomic_cr](Classes/classatomic__cr.md#function-atomic-cr)**(unsigned char * memory) |
| [response_t](Classes/classatomic__cr.md#using-response-t) | **[request](Classes/classatomic__cr.md#function-request)**([request_t](Classes/classatomic__cr.md#using-request-t) value) |
| [element](Classes/classatomic__cr_1_1element.md) * | **[pop](Classes/classatomic__cr.md#function-pop)**() |

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| std::atomic< unsigned > * | **[id](Classes/classatomic__cr.md#variable-id)**  |
| std::atomic< unsigned > * | **[count](Classes/classatomic__cr.md#variable-count)**  |

## Detailed Description

```cpp
template <unsigned size>
class atomic_cr;
```

## Public Types Documentation

### enum @0

| Enumerator | Value | Description |
| ---------- | ----- | ----------- |
| UNUSED | 0ul|   |




### using request_t

```cpp
using atomic_cr< size >::request_t =  unsigned;
```


### using response_t

```cpp
using atomic_cr< size >::response_t =  unsigned;
```


## Public Functions Documentation

### function atomic_cr

```cpp
inline explicit atomic_cr(
    unsigned char * memory
)
```


### function request

```cpp
inline response_t request(
    request_t value
)
```


### function pop

```cpp
inline element * pop()
```


## Public Attributes Documentation

### variable id

```cpp
std::atomic< unsigned > * id = 0;
```


### variable count

```cpp
std::atomic< unsigned > * count = 0;
```


-------------------------------

Updated on 2022-04-30 at 06:56:37 +0000