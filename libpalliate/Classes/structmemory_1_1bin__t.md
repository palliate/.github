---
title: memory::bin_t

---

# memory::bin_t






`#include <bin.h>`

Inherits from [memory::element_t](Classes/structmemory_1_1element__t.md)

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[bin_t](Classes/structmemory_1_1bin__t.md#function-bin-t)**() |
| | **[bin_t](Classes/structmemory_1_1bin__t.md#function-bin-t)**([node_t](Classes/structmemory_1_1node__t.md) * _first) |
| | **[~bin_t](Classes/structmemory_1_1bin__t.md#function-~bin-t)**() |
| virtual void | **[print](Classes/structmemory_1_1bin__t.md#function-print)**() override |
| [node_t](Classes/structmemory_1_1node__t.md) * | **[pop](Classes/structmemory_1_1bin__t.md#function-pop)**() |
| void | **[push](Classes/structmemory_1_1bin__t.md#function-push)**([node_t](Classes/structmemory_1_1node__t.md) * node) |
| void | **[insert_after](Classes/structmemory_1_1bin__t.md#function-insert-after)**([bin_t](Classes/structmemory_1_1bin__t.md) * bin) |
| void | **[insert_before](Classes/structmemory_1_1bin__t.md#function-insert-before)**([bin_t](Classes/structmemory_1_1bin__t.md) * bin) |

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| [bin_t](Classes/structmemory_1_1bin__t.md) * | **[next](Classes/structmemory_1_1bin__t.md#variable-next)**  |
| [bin_t](Classes/structmemory_1_1bin__t.md) * | **[prev](Classes/structmemory_1_1bin__t.md#variable-prev)**  |
| [node_t](Classes/structmemory_1_1node__t.md) * | **[first](Classes/structmemory_1_1bin__t.md#variable-first)**  |

## Additional inherited members

**Public Functions inherited from [memory::element_t](Classes/structmemory_1_1element__t.md)**

|                | Name           |
| -------------- | -------------- |
| | **[element_t](Classes/structmemory_1_1element__t.md#function-element-t)**(unsigned _pages) |
| virtual | **[~element_t](Classes/structmemory_1_1element__t.md#function-~element-t)**() |

**Public Attributes inherited from [memory::element_t](Classes/structmemory_1_1element__t.md)**

|                | Name           |
| -------------- | -------------- |
| unsigned | **[pages](Classes/structmemory_1_1element__t.md#variable-pages)**  |


## Public Functions Documentation

### function bin_t

```cpp
inline bin_t()
```


### function bin_t

```cpp
explicit bin_t(
    node_t * _first
)
```


### function ~bin_t

```cpp
~bin_t()
```


### function print

```cpp
virtual void print() override
```


**Reimplements**: [memory::element_t::print](Classes/structmemory_1_1element__t.md#function-print)


### function pop

```cpp
node_t * pop()
```


### function push

```cpp
void push(
    node_t * node
)
```


### function insert_after

```cpp
void insert_after(
    bin_t * bin
)
```


### function insert_before

```cpp
void insert_before(
    bin_t * bin
)
```


## Public Attributes Documentation

### variable next

```cpp
bin_t * next = nullptr;
```


### variable prev

```cpp
bin_t * prev = nullptr;
```


### variable first

```cpp
node_t * first = nullptr;
```


-------------------------------

Updated on 2022-04-30 at 06:56:37 +0000