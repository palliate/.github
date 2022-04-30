---
title: memory::element_t

---

# memory::element_t






`#include <element.h>`

Inherited by [memory::bin_t](Classes/structmemory_1_1bin__t.md), [memory::node_t](Classes/structmemory_1_1node__t.md)

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[element_t](Classes/structmemory_1_1element__t.md#function-element-t)**(unsigned _pages) |
| virtual | **[~element_t](Classes/structmemory_1_1element__t.md#function-~element-t)**() |
| virtual void | **[print](Classes/structmemory_1_1element__t.md#function-print)**() =0 |

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| unsigned | **[pages](Classes/structmemory_1_1element__t.md#variable-pages)**  |

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


**Reimplemented by**: [memory::bin_t::print](Classes/structmemory_1_1bin__t.md#function-print), [memory::node_t::print](Classes/structmemory_1_1node__t.md#function-print)


## Public Attributes Documentation

### variable pages

```cpp
unsigned pages = 0;
```


-------------------------------

Updated on 2022-04-30 at 06:56:37 +0000