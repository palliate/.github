---
title: memory::client

---

# memory::client






`#include <client.h>`

Inherits from [memory::manager](Classes/classmemory_1_1manager.md)

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[client](Classes/classmemory_1_1client.md#function-client)**(std::span< unsigned char > _base) |
| | **[~client](Classes/classmemory_1_1client.md#function-~client)**() override |
| virtual void | **[print](Classes/classmemory_1_1client.md#function-print)**() override |

## Protected Functions

|                | Name           |
| -------------- | -------------- |
| virtual [offset_t](Namespaces/namespacememory.md#using-offset-t) | **[_alloc](Classes/classmemory_1_1client.md#function--alloc)**(unsigned pages) override |
| virtual unsigned | **[_free](Classes/classmemory_1_1client.md#function--free)**([offset_t](Namespaces/namespacememory.md#using-offset-t) address) override |

## Additional inherited members

**Public Functions inherited from [memory::manager](Classes/classmemory_1_1manager.md)**

|                | Name           |
| -------------- | -------------- |
| | **[manager](Classes/classmemory_1_1manager.md#function-manager)**(std::span< unsigned char > _base) |
| virtual | **[~manager](Classes/classmemory_1_1manager.md#function-~manager)**() =default |
| unsigned char * | **[alloc](Classes/classmemory_1_1manager.md#function-alloc)**(size_t bytes) |
| unsigned | **[free](Classes/classmemory_1_1manager.md#function-free)**(unsigned char * address) |
| [offset_t](Namespaces/namespacememory.md#using-offset-t) | **[to_offset](Classes/classmemory_1_1manager.md#function-to-offset)**(unsigned char * ptr) |

**Protected Functions inherited from [memory::manager](Classes/classmemory_1_1manager.md)**

|                | Name           |
| -------------- | -------------- |
| unsigned char * | **[to_ptr](Classes/classmemory_1_1manager.md#function-to-ptr)**([offset_t](Namespaces/namespacememory.md#using-offset-t) offset) |
| unsigned | **[size_to_pages](Classes/classmemory_1_1manager.md#function-size-to-pages)**(unsigned size) |

**Protected Attributes inherited from [memory::manager](Classes/classmemory_1_1manager.md)**

|                | Name           |
| -------------- | -------------- |
| unsigned char * | **[base](Classes/classmemory_1_1manager.md#variable-base)**  |
| size_t | **[size](Classes/classmemory_1_1manager.md#variable-size)**  |
| [atomic_cr](Classes/classatomic__cr.md)< 8 > * | **[queue](Classes/classmemory_1_1manager.md#variable-queue)**  |
| constexpr size_t | **[PAGE_SIZE](Classes/classmemory_1_1manager.md#variable-page-size)**  |


## Public Functions Documentation

### function client

```cpp
explicit client(
    std::span< unsigned char > _base
)
```


### function ~client

```cpp
~client() override
```


### function print

```cpp
virtual void print() override
```


**Reimplements**: [memory::manager::print](Classes/classmemory_1_1manager.md#function-print)


## Protected Functions Documentation

### function _alloc

```cpp
virtual offset_t _alloc(
    unsigned pages
) override
```


**Reimplements**: [memory::manager::_alloc](Classes/classmemory_1_1manager.md#function--alloc)


### function _free

```cpp
virtual unsigned _free(
    offset_t address
) override
```


**Reimplements**: [memory::manager::_free](Classes/classmemory_1_1manager.md#function--free)


-------------------------------

Updated on 2022-04-30 at 06:56:37 +0000