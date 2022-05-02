---
title: atomic_cr
parent: Classes
grand_parent: libpalliate
layout: default
---

# atomic_cr



 [More...](#detailed-description)


`#include <atomic_cr.h>`

## Public Classes

|                | Name           |
| -------------- | -------------- |
| class | **[element](/libpalliate/generated/Classes/classatomic__cr_1_1element)**  |

## Public Types

|                | Name           |
| -------------- | -------------- |
| enum unsigned | **[@2](/libpalliate/generated/Classes/classatomic__cr#enum-@2)** { UNUSED = 0ul} |
| using unsigned | **[request_t](/libpalliate/generated/Classes/classatomic__cr#using-request-t)**  |
| using unsigned | **[response_t](/libpalliate/generated/Classes/classatomic__cr#using-response-t)**  |

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[atomic_cr](/libpalliate/generated/Classes/classatomic__cr#function-atomic-cr)**(unsigned char * memory) |
| [response_t](/libpalliate/generated/Classes/classatomic__cr#using-response-t) | **[request](/libpalliate/generated/Classes/classatomic__cr#function-request)**([request_t](/libpalliate/generated/Classes/classatomic__cr#using-request-t) value) |
| [element](/libpalliate/generated/Classes/classatomic__cr_1_1element) * | **[pop](/libpalliate/generated/Classes/classatomic__cr#function-pop)**() |

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| std::atomic< unsigned > * | **[id](/libpalliate/generated/Classes/classatomic__cr#variable-id)**  |
| std::atomic< unsigned > * | **[count](/libpalliate/generated/Classes/classatomic__cr#variable-count)**  |

## Detailed Description

```cpp
template <unsigned size>
class atomic_cr;
```

## Public Types Documentation

### enum @2

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



_Automatically updated on 2022-05-02 at 01:42:11 +0000._