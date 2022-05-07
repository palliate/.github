---
title: memory::element_t
parent: Classes
grand_parent: libpalliate
layout: default
---

# memory::element_t






`#include <element.h>`

Inherited by [memory::bin_t](/libpalliate/generated/Classes/structmemory_1_1bin__t), [memory::node_t](/libpalliate/generated/Classes/structmemory_1_1node__t)

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[element_t](/libpalliate/generated/Classes/structmemory_1_1element__t#function-element-t)**(unsigned _pages) |
| virtual | **[~element_t](/libpalliate/generated/Classes/structmemory_1_1element__t#function-~element-t)**() |
| virtual void | **[print](/libpalliate/generated/Classes/structmemory_1_1element__t#function-print)**() =0 |

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| unsigned | **[pages](/libpalliate/generated/Classes/structmemory_1_1element__t#variable-pages)**  |

## Public Functions Documentation

### function element_t

```cpp
inline explicit element_t(
    unsigned _pages
)
```


### function ~element_t

```cpp
inline virtual ~element_t()
```


### function print

```cpp
virtual void print() =0
```


**Reimplemented by**: [memory::bin_t::print](/libpalliate/generated/Classes/structmemory_1_1bin__t#function-print), [memory::node_t::print](/libpalliate/generated/Classes/structmemory_1_1node__t#function-print)


## Public Attributes Documentation

### variable pages

```cpp
unsigned pages = 0;
```



_Automatically updated on 2022-05-07 at 23:14:50 +0000._