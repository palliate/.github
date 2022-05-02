---
title: memory::manager
parent: Classes
grand_parent: libpalliate
layout: default
---

# memory::manager






`#include <manager.h>`

Inherited by [memory::client](/libpalliate/generated/Classes/classmemory_1_1client), [memory::server](/libpalliate/generated/Classes/classmemory_1_1server)

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[manager](/libpalliate/generated/Classes/classmemory_1_1manager#function-manager)**(std::span< unsigned char > _base) |
| virtual | **[~manager](/libpalliate/generated/Classes/classmemory_1_1manager#function-~manager)**() =default |
| unsigned char * | **[alloc](/libpalliate/generated/Classes/classmemory_1_1manager#function-alloc)**(size_t bytes) |
| unsigned | **[free](/libpalliate/generated/Classes/classmemory_1_1manager#function-free)**(unsigned char * address) |
| virtual void | **[print](/libpalliate/generated/Classes/classmemory_1_1manager#function-print)**() =0 |
| [offset_t](/libpalliate/generated/Namespaces/namespacememory#using-offset-t) | **[to_offset](/libpalliate/generated/Classes/classmemory_1_1manager#function-to-offset)**(unsigned char * ptr) |

## Protected Functions

|                | Name           |
| -------------- | -------------- |
| unsigned char * | **[to_ptr](/libpalliate/generated/Classes/classmemory_1_1manager#function-to-ptr)**([offset_t](/libpalliate/generated/Namespaces/namespacememory#using-offset-t) offset) |
| unsigned | **[size_to_pages](/libpalliate/generated/Classes/classmemory_1_1manager#function-size-to-pages)**(unsigned size) |
| virtual [offset_t](/libpalliate/generated/Namespaces/namespacememory#using-offset-t) | **[_alloc](/libpalliate/generated/Classes/classmemory_1_1manager#function--alloc)**(unsigned pages) =0 |
| virtual unsigned | **[_free](/libpalliate/generated/Classes/classmemory_1_1manager#function--free)**([offset_t](/libpalliate/generated/Namespaces/namespacememory#using-offset-t) address) =0 |

## Protected Attributes

|                | Name           |
| -------------- | -------------- |
| unsigned char * | **[base](/libpalliate/generated/Classes/classmemory_1_1manager#variable-base)**  |
| size_t | **[size](/libpalliate/generated/Classes/classmemory_1_1manager#variable-size)**  |
| [atomic_cr](/libpalliate/generated/Classes/classatomic__cr)< 8 > * | **[queue](/libpalliate/generated/Classes/classmemory_1_1manager#variable-queue)**  |
| constexpr size_t | **[PAGE_SIZE](/libpalliate/generated/Classes/classmemory_1_1manager#variable-page-size)**  |

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


**Reimplemented by**: [memory::client::print](/libpalliate/generated/Classes/classmemory_1_1client#function-print), [memory::server::print](/libpalliate/generated/Classes/classmemory_1_1server#function-print)


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


**Reimplemented by**: [memory::server::_alloc](/libpalliate/generated/Classes/classmemory_1_1server#function--alloc), [memory::client::_alloc](/libpalliate/generated/Classes/classmemory_1_1client#function--alloc)


### function _free

```cpp
virtual unsigned _free(
    offset_t address
) =0
```


**Reimplemented by**: [memory::server::_free](/libpalliate/generated/Classes/classmemory_1_1server#function--free), [memory::client::_free](/libpalliate/generated/Classes/classmemory_1_1client#function--free)


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



_Automatically updated on 2022-05-02 at 01:42:07 +0000._