---
title: memory

---

# memory



## Classes

|                | Name           |
| -------------- | -------------- |
| struct | **[memory::bin_t](Classes/structmemory_1_1bin__t.md)**  |
| class | **[memory::client](Classes/classmemory_1_1client.md)**  |
| struct | **[memory::element_t](Classes/structmemory_1_1element__t.md)**  |
| class | **[memory::manager](Classes/classmemory_1_1manager.md)**  |
| class | **[memory::memory_map](Classes/classmemory_1_1memory__map.md)**  |
| struct | **[memory::node_t](Classes/structmemory_1_1node__t.md)**  |
| class | **[memory::server](Classes/classmemory_1_1server.md)**  |

## Types

|                | Name           |
| -------------- | -------------- |
| enum unsigned | **[@1](Namespaces/namespacememory.md#enum-@1)** { UNUSED = 0ul, INVALID = UINT32_MAX, CLAIM = 1ul << 31, WAIVE = 1ul << 30, PRINT = 1ul << 29} |
| using unsigned | **[offset_t](Namespaces/namespacememory.md#using-offset-t)**  |

## Attributes

|                | Name           |
| -------------- | -------------- |
| constexpr unsigned | **[MAGIC](Namespaces/namespacememory.md#variable-magic)**  |

## Types Documentation

### enum @1

| Enumerator | Value | Description |
| ---------- | ----- | ----------- |
| UNUSED | 0ul|   |
| INVALID | UINT32_MAX|   |
| CLAIM | 1ul << 31|   |
| WAIVE | 1ul << 30|   |
| PRINT | 1ul << 29|   |




### using offset_t

```cpp
using memory::offset_t = typedef unsigned;
```




## Attributes Documentation

### variable MAGIC

```cpp
static constexpr unsigned MAGIC = 0xC0FFEEul;
```





-------------------------------

Updated on 2022-04-30 at 06:56:37 +0000