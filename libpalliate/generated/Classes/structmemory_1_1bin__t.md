---
title: memory::bin_t
parent: Classes
grand_parent: libpalliate
layout: default
---

# memory::bin_t






`#include <bin.h>`

Inherits from [memory::element_t](/libpalliate/generated/Classes/structmemory_1_1element__t)

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[bin_t](/libpalliate/generated/Classes/structmemory_1_1bin__t#function-bin-t)**() |
| | **[bin_t](/libpalliate/generated/Classes/structmemory_1_1bin__t#function-bin-t)**([node_t](/libpalliate/generated/Classes/structmemory_1_1node__t) * _first) |
| | **[~bin_t](/libpalliate/generated/Classes/structmemory_1_1bin__t#function-~bin-t)**() |
| virtual void | **[print](/libpalliate/generated/Classes/structmemory_1_1bin__t#function-print)**() override |
| [node_t](/libpalliate/generated/Classes/structmemory_1_1node__t) * | **[pop](/libpalliate/generated/Classes/structmemory_1_1bin__t#function-pop)**() |
| void | **[push](/libpalliate/generated/Classes/structmemory_1_1bin__t#function-push)**([node_t](/libpalliate/generated/Classes/structmemory_1_1node__t) * node) |
| void | **[insert_after](/libpalliate/generated/Classes/structmemory_1_1bin__t#function-insert-after)**([bin_t](/libpalliate/generated/Classes/structmemory_1_1bin__t) * bin) |
| void | **[insert_before](/libpalliate/generated/Classes/structmemory_1_1bin__t#function-insert-before)**([bin_t](/libpalliate/generated/Classes/structmemory_1_1bin__t) * bin) |

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| [bin_t](/libpalliate/generated/Classes/structmemory_1_1bin__t) * | **[next](/libpalliate/generated/Classes/structmemory_1_1bin__t#variable-next)**  |
| [bin_t](/libpalliate/generated/Classes/structmemory_1_1bin__t) * | **[prev](/libpalliate/generated/Classes/structmemory_1_1bin__t#variable-prev)**  |
| [node_t](/libpalliate/generated/Classes/structmemory_1_1node__t) * | **[first](/libpalliate/generated/Classes/structmemory_1_1bin__t#variable-first)**  |

## Additional inherited members

**Public Functions inherited from [memory::element_t](/libpalliate/generated/Classes/structmemory_1_1element__t)**

|                | Name           |
| -------------- | -------------- |
| | **[element_t](/libpalliate/generated/Classes/structmemory_1_1element__t#function-element-t)**(unsigned _pages) |
| virtual | **[~element_t](/libpalliate/generated/Classes/structmemory_1_1element__t#function-~element-t)**() |

**Public Attributes inherited from [memory::element_t](/libpalliate/generated/Classes/structmemory_1_1element__t)**

|                | Name           |
| -------------- | -------------- |
| unsigned | **[pages](/libpalliate/generated/Classes/structmemory_1_1element__t#variable-pages)**  |


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


**Reimplements**: [memory::element_t::print](/libpalliate/generated/Classes/structmemory_1_1element__t#function-print)


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



_Automatically updated on 2022-05-07 at 23:06:39 +0000._