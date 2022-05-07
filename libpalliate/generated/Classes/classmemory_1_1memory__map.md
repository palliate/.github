---
title: memory::memory_map
parent: Classes
grand_parent: libpalliate
layout: default
---

# memory::memory_map






`#include <memory_map.h>`

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[memory_map](/libpalliate/generated/Classes/classmemory_1_1memory__map#function-memory-map)**(unsigned _maxsize) |
| | **[~memory_map](/libpalliate/generated/Classes/classmemory_1_1memory__map#function-~memory-map)**() |
| void | **[print](/libpalliate/generated/Classes/classmemory_1_1memory__map#function-print)**() |
| [bin_t](/libpalliate/generated/Classes/structmemory_1_1bin__t) * | **[find_bin](/libpalliate/generated/Classes/classmemory_1_1memory__map#function-find-bin)**(unsigned pages) |
| void | **[free](/libpalliate/generated/Classes/classmemory_1_1memory__map#function-free)**([pkey_t](/libpalliate/generated/Files/patricia_8h#using-pkey-t) key) |
| void | **[_free](/libpalliate/generated/Classes/classmemory_1_1memory__map#function--free)**([node_t](/libpalliate/generated/Classes/structmemory_1_1node__t) * node) |
| [node_t](/libpalliate/generated/Classes/structmemory_1_1node__t) * | **[alloc](/libpalliate/generated/Classes/classmemory_1_1memory__map#function-alloc)**(unsigned pages) |

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



_Automatically updated on 2022-05-07 at 23:06:39 +0000._