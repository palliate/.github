---
title: memory::server
parent: Classes
grand_parent: libpalliate
layout: default
---

# memory::server






`#include <server.h>`

Inherits from [memory::manager](/libpalliate/generated/Classes/classmemory_1_1manager)

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[server](/libpalliate/generated/Classes/classmemory_1_1server#function-server)**(std::span< unsigned char > _base) |
| | **[~server](/libpalliate/generated/Classes/classmemory_1_1server#function-~server)**() override |
| void | **[run](/libpalliate/generated/Classes/classmemory_1_1server#function-run)**() |
| virtual void | **[print](/libpalliate/generated/Classes/classmemory_1_1server#function-print)**() override |

## Protected Functions

|                | Name           |
| -------------- | -------------- |
| virtual [offset_t](/libpalliate/generated/Namespaces/namespacememory#using-offset-t) | **[_alloc](/libpalliate/generated/Classes/classmemory_1_1server#function--alloc)**(unsigned pages) |
| virtual unsigned | **[_free](/libpalliate/generated/Classes/classmemory_1_1server#function--free)**([offset_t](/libpalliate/generated/Namespaces/namespacememory#using-offset-t) address) |

## Additional inherited members

**Public Functions inherited from [memory::manager](/libpalliate/generated/Classes/classmemory_1_1manager)**

|                | Name           |
| -------------- | -------------- |
| | **[manager](/libpalliate/generated/Classes/classmemory_1_1manager#function-manager)**(std::span< unsigned char > _base) |
| virtual | **[~manager](/libpalliate/generated/Classes/classmemory_1_1manager#function-~manager)**() =default |
| unsigned char * | **[alloc](/libpalliate/generated/Classes/classmemory_1_1manager#function-alloc)**(size_t bytes) |
| unsigned | **[free](/libpalliate/generated/Classes/classmemory_1_1manager#function-free)**(unsigned char * address) |
| [offset_t](/libpalliate/generated/Namespaces/namespacememory#using-offset-t) | **[to_offset](/libpalliate/generated/Classes/classmemory_1_1manager#function-to-offset)**(unsigned char * ptr) |

**Protected Functions inherited from [memory::manager](/libpalliate/generated/Classes/classmemory_1_1manager)**

|                | Name           |
| -------------- | -------------- |
| unsigned char * | **[to_ptr](/libpalliate/generated/Classes/classmemory_1_1manager#function-to-ptr)**([offset_t](/libpalliate/generated/Namespaces/namespacememory#using-offset-t) offset) |
| unsigned | **[size_to_pages](/libpalliate/generated/Classes/classmemory_1_1manager#function-size-to-pages)**(unsigned size) |

**Protected Attributes inherited from [memory::manager](/libpalliate/generated/Classes/classmemory_1_1manager)**

|                | Name           |
| -------------- | -------------- |
| unsigned char * | **[base](/libpalliate/generated/Classes/classmemory_1_1manager#variable-base)**  |
| size_t | **[size](/libpalliate/generated/Classes/classmemory_1_1manager#variable-size)**  |
| [atomic_cr](/libpalliate/generated/Classes/classatomic__cr)< 8 > * | **[queue](/libpalliate/generated/Classes/classmemory_1_1manager#variable-queue)**  |
| constexpr size_t | **[PAGE_SIZE](/libpalliate/generated/Classes/classmemory_1_1manager#variable-page-size)**  |


## Public Functions Documentation

### function server

```cpp
explicit server(
    std::span< unsigned char > _base
)
```


### function ~server

```cpp
~server() override
```


### function run

```cpp
void run()
```


### function print

```cpp
virtual void print() override
```


**Reimplements**: [memory::manager::print](/libpalliate/generated/Classes/classmemory_1_1manager#function-print)


## Protected Functions Documentation

### function _alloc

```cpp
virtual offset_t _alloc(
    unsigned pages
)
```


**Reimplements**: [memory::manager::_alloc](/libpalliate/generated/Classes/classmemory_1_1manager#function--alloc)


### function _free

```cpp
virtual unsigned _free(
    offset_t address
)
```


**Reimplements**: [memory::manager::_free](/libpalliate/generated/Classes/classmemory_1_1manager#function--free)



_Automatically updated on 2022-05-02 at 01:42:11 +0000._