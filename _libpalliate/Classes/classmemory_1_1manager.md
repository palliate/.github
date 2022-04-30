---
title: memory::manager

---

# memory::manager






`#include <manager.h>`

Inherited by [memory::client](Classes/classmemory_1_1client.md), [memory::server](Classes/classmemory_1_1server.md)

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[manager](Classes/classmemory_1_1manager.md#function-manager)**(std::span< unsigned char > _base) |
| virtual | **[~manager](Classes/classmemory_1_1manager.md#function-~manager)**() =default |
| unsigned char * | **[alloc](Classes/classmemory_1_1manager.md#function-alloc)**(size_t bytes) |
| unsigned | **[free](Classes/classmemory_1_1manager.md#function-free)**(unsigned char * address) |
| virtual void | **[print](Classes/classmemory_1_1manager.md#function-print)**() =0 |
| [offset_t](Namespaces/namespacememory.md#using-offset-t) | **[to_offset](Classes/classmemory_1_1manager.md#function-to-offset)**(unsigned char * ptr) |

## Protected Functions

|                | Name           |
| -------------- | -------------- |
| unsigned char * | **[to_ptr](Classes/classmemory_1_1manager.md#function-to-ptr)**([offset_t](Namespaces/namespacememory.md#using-offset-t) offset) |
| unsigned | **[size_to_pages](Classes/classmemory_1_1manager.md#function-size-to-pages)**(unsigned size) |
| virtual [offset_t](Namespaces/namespacememory.md#using-offset-t) | **[_alloc](Classes/classmemory_1_1manager.md#function--alloc)**(unsigned pages) =0 |
| virtual unsigned | **[_free](Classes/classmemory_1_1manager.md#function--free)**([offset_t](Namespaces/namespacememory.md#using-offset-t) address) =0 |

## Protected Attributes

|                | Name           |
| -------------- | -------------- |
| unsigned char * | **[base](Classes/classmemory_1_1manager.md#variable-base)**  |
| size_t | **[size](Classes/classmemory_1_1manager.md#variable-size)**  |
| [atomic_cr](Classes/classatomic__cr.md)< 8 > * | **[queue](Classes/classmemory_1_1manager.md#variable-queue)**  |
| constexpr size_t | **[PAGE_SIZE](Classes/classmemory_1_1manager.md#variable-page-size)**  |

## Public Functions Documentation

### function manager

```cpp
explicit manager(
    std::span< unsigned char > _base
)
```


### function ~manager

```cpp
virtual ~manager() =default
```


### function alloc

```cpp
unsigned char * alloc(
    size_t bytes
)
```


### function free

```cpp
unsigned free(
    unsigned char * address
)
```


### function print

```cpp
virtual void print() =0
```


**Reimplemented by**: [memory::client::print](Classes/classmemory_1_1client.md#function-print), [memory::server::print](Classes/classmemory_1_1server.md#function-print)


### function to_offset

```cpp
offset_t to_offset(
    unsigned char * ptr
)
```


## Protected Functions Documentation

### function to_ptr

```cpp
unsigned char * to_ptr(
    offset_t offset
)
```


### function size_to_pages

```cpp
unsigned size_to_pages(
    unsigned size
)
```


### function _alloc

```cpp
virtual offset_t _alloc(
    unsigned pages
) =0
```


**Reimplemented by**: [memory::server::_alloc](Classes/classmemory_1_1server.md#function--alloc), [memory::client::_alloc](Classes/classmemory_1_1client.md#function--alloc)


### function _free

```cpp
virtual unsigned _free(
    offset_t address
) =0
```


**Reimplemented by**: [memory::server::_free](Classes/classmemory_1_1server.md#function--free), [memory::client::_free](Classes/classmemory_1_1client.md#function--free)


## Protected Attributes Documentation

### variable base

```cpp
unsigned char * base;
```


### variable size

```cpp
size_t size;
```


### variable queue

```cpp
atomic_cr< 8 > * queue;
```


### variable PAGE_SIZE

```cpp
static constexpr size_t PAGE_SIZE = 64;
```


-------------------------------

Updated on 2022-04-30 at 06:56:37 +0000