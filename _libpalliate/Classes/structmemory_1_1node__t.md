---
title: memory::node_t

---

# memory::node_t






`#include <node.h>`

Inherits from [memory::element_t](Classes/structmemory_1_1element__t.md), [patricia::leaf_t](Classes/structpatricia_1_1leaf__t.md), [patricia::element_t](Classes/structpatricia_1_1element__t.md)

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[node_t](Classes/structmemory_1_1node__t.md#function-node-t)**(unsigned _pages, unsigned _offset) |
| | **[~node_t](Classes/structmemory_1_1node__t.md#function-~node-t)**() |
| void | **[unlink](Classes/structmemory_1_1node__t.md#function-unlink)**() |
| virtual std::string | **[to_str](Classes/structmemory_1_1node__t.md#function-to-str)**() override |
| virtual void | **[print](Classes/structmemory_1_1node__t.md#function-print)**() override |

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| bool | **[in_use](Classes/structmemory_1_1node__t.md#variable-in-use)**  |
| [node_t](Classes/structmemory_1_1node__t.md) * | **[next](Classes/structmemory_1_1node__t.md#variable-next)**  |
| [memory::element_t](Classes/structmemory_1_1element__t.md) * | **[prev](Classes/structmemory_1_1node__t.md#variable-prev)**  |

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

**Public Functions inherited from [patricia::leaf_t](Classes/structpatricia_1_1leaf__t.md)**

|                | Name           |
| -------------- | -------------- |
| | **[leaf_t](Classes/structpatricia_1_1leaf__t.md#function-leaf-t)**([pkey_t](Files/patricia_8h.md#using-pkey-t) _key) |
| | **[~leaf_t](Classes/structpatricia_1_1leaf__t.md#function-~leaf-t)**() |
| [leaf_t](Classes/structpatricia_1_1leaf__t.md) * | **[find_next](Classes/structpatricia_1_1leaf__t.md#function-find-next)**() |
| [leaf_t](Classes/structpatricia_1_1leaf__t.md) * | **[find_prev](Classes/structpatricia_1_1leaf__t.md#function-find-prev)**() |

**Public Functions inherited from [patricia::element_t](Classes/structpatricia_1_1element__t.md)**

|                | Name           |
| -------------- | -------------- |
| [pkey_t](Files/patricia_8h.md#using-pkey-t) | **[mask](Classes/structpatricia_1_1element__t.md#function-mask)**() |
| | **[element_t](Classes/structpatricia_1_1element__t.md#function-element-t)**([pkey_t](Files/patricia_8h.md#using-pkey-t) _key, uint8_t _branchbit) |
| virtual | **[~element_t](Classes/structpatricia_1_1element__t.md#function-~element-t)**() |

**Public Attributes inherited from [patricia::element_t](Classes/structpatricia_1_1element__t.md)**

|                | Name           |
| -------------- | -------------- |
| [pkey_t](Files/patricia_8h.md#using-pkey-t) | **[key](Classes/structpatricia_1_1element__t.md#variable-key)**  |
| [node_t](Classes/structpatricia_1_1node__t.md) * | **[parent](Classes/structpatricia_1_1element__t.md#variable-parent)**  |
| uint8_t | **[branchbit](Classes/structpatricia_1_1element__t.md#variable-branchbit)**  |


## Public Functions Documentation

### function node_t

```cpp
inline node_t(
    unsigned _pages,
    unsigned _offset
)
```


### function ~node_t

```cpp
inline ~node_t()
```


### function unlink

```cpp
void unlink()
```


### function to_str

```cpp
virtual std::string to_str() override
```


**Reimplements**: [patricia::leaf_t::to_str](Classes/structpatricia_1_1leaf__t.md#function-to-str)


### function print

```cpp
virtual void print() override
```


**Reimplements**: [memory::element_t::print](Classes/structmemory_1_1element__t.md#function-print)


## Public Attributes Documentation

### variable in_use

```cpp
bool in_use = false;
```


### variable next

```cpp
node_t * next = nullptr;
```


### variable prev

```cpp
memory::element_t * prev = nullptr;
```


-------------------------------

Updated on 2022-04-30 at 06:56:37 +0000