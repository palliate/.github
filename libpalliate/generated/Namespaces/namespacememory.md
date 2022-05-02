---
title: memory
parent: Namespaces
grand_parent: libpalliate
layout: default
---

# memory



## Classes

|                | Name           |
| -------------- | -------------- |
| struct | **[memory::bin_t](/libpalliate/generated/Classes/structmemory_1_1bin__t)**  |
| class | **[memory::client](/libpalliate/generated/Classes/classmemory_1_1client)**  |
| struct | **[memory::element_t](/libpalliate/generated/Classes/structmemory_1_1element__t)**  |
| class | **[memory::manager](/libpalliate/generated/Classes/classmemory_1_1manager)**  |
| class | **[memory::memory_map](/libpalliate/generated/Classes/classmemory_1_1memory__map)**  |
| struct | **[memory::node_t](/libpalliate/generated/Classes/structmemory_1_1node__t)**  |
| class | **[memory::server](/libpalliate/generated/Classes/classmemory_1_1server)**  |

## Types

|                | Name           |
| -------------- | -------------- |
| enum unsigned | **[@3](/libpalliate/generated/Namespaces/namespacememory#enum-@3)** { UNUSED = 0ul, INVALID = UINT32_MAX, CLAIM = 1ul << 31, WAIVE = 1ul << 30, PRINT = 1ul << 29} |
| using unsigned | **[offset_t](/libpalliate/generated/Namespaces/namespacememory#using-offset-t)**  |

## Attributes

|                | Name           |
| -------------- | -------------- |
| constexpr unsigned | **[MAGIC](/libpalliate/generated/Namespaces/namespacememory#variable-magic)**  |

## Types Documentation

### enum @3

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






_Automatically updated on 2022-05-02 at 01:42:11 +0000._