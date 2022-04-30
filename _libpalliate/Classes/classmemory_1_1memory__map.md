---
title: memory::memory_map

---

# memory::memory_map






`#include <memory_map.h>`

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[memory_map](Classes/classmemory_1_1memory__map.md#function-memory-map)**(unsigned _maxsize) |
| | **[~memory_map](Classes/classmemory_1_1memory__map.md#function-~memory-map)**() |
| void | **[print](Classes/classmemory_1_1memory__map.md#function-print)**() |
| [bin_t](Classes/structmemory_1_1bin__t.md) * | **[find_bin](Classes/classmemory_1_1memory__map.md#function-find-bin)**(unsigned pages) |
| void | **[free](Classes/classmemory_1_1memory__map.md#function-free)**([pkey_t](Files/patricia_8h.md#using-pkey-t) key) |
| void | **[_free](Classes/classmemory_1_1memory__map.md#function--free)**([node_t](Classes/structmemory_1_1node__t.md) * node) |
| [node_t](Classes/structmemory_1_1node__t.md) * | **[alloc](Classes/classmemory_1_1memory__map.md#function-alloc)**(unsigned pages) |

## Public Functions Documentation

### function memory_map

```cpp
explicit memory_map(
    unsigned _maxsize
)
```


### function ~memory_map

```cpp
~memory_map()
```


### function print

```cpp
void print()
```


### function find_bin

```cpp
bin_t * find_bin(
    unsigned pages
)
```


### function free

```cpp
void free(
    pkey_t key
)
```


### function _free

```cpp
void _free(
    node_t * node
)
```


### function alloc

```cpp
node_t * alloc(
    unsigned pages
)
```


-------------------------------

Updated on 2022-04-30 at 06:56:37 +0000