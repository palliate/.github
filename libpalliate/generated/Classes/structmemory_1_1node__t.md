---
title: memory::node_t
parent: Classes
grand_parent: libpalliate
layout: default
---

# memory::node_t






`#include <node.h>`

Inherits from [memory::element_t](/libpalliate/generated/Classes/structmemory_1_1element__t), [patricia::leaf_t](/libpalliate/generated/Classes/structpatricia_1_1leaf__t), [patricia::element_t](/libpalliate/generated/Classes/structpatricia_1_1element__t)

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[node_t](/libpalliate/generated/Classes/structmemory_1_1node__t#function-node-t)**(unsigned _pages, unsigned _offset) |
| | **[~node_t](/libpalliate/generated/Classes/structmemory_1_1node__t#function-~node-t)**() |
| void | **[unlink](/libpalliate/generated/Classes/structmemory_1_1node__t#function-unlink)**() |
| virtual std::string | **[to_str](/libpalliate/generated/Classes/structmemory_1_1node__t#function-to-str)**() override |
| virtual void | **[print](/libpalliate/generated/Classes/structmemory_1_1node__t#function-print)**() override |

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| bool | **[in_use](/libpalliate/generated/Classes/structmemory_1_1node__t#variable-in-use)**  |
| [node_t](/libpalliate/generated/Classes/structmemory_1_1node__t) * | **[next](/libpalliate/generated/Classes/structmemory_1_1node__t#variable-next)**  |
| [memory::element_t](/libpalliate/generated/Classes/structmemory_1_1element__t) * | **[prev](/libpalliate/generated/Classes/structmemory_1_1node__t#variable-prev)**  |

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

**Public Functions inherited from [patricia::leaf_t](/libpalliate/generated/Classes/structpatricia_1_1leaf__t)**

|                | Name           |
| -------------- | -------------- |
| | **[leaf_t](/libpalliate/generated/Classes/structpatricia_1_1leaf__t#function-leaf-t)**([pkey_t](/libpalliate/generated/Files/patricia_8h#using-pkey-t) _key) |
| | **[~leaf_t](/libpalliate/generated/Classes/structpatricia_1_1leaf__t#function-~leaf-t)**() |
| [leaf_t](/libpalliate/generated/Classes/structpatricia_1_1leaf__t) * | **[find_next](/libpalliate/generated/Classes/structpatricia_1_1leaf__t#function-find-next)**() |
| [leaf_t](/libpalliate/generated/Classes/structpatricia_1_1leaf__t) * | **[find_prev](/libpalliate/generated/Classes/structpatricia_1_1leaf__t#function-find-prev)**() |

**Public Functions inherited from [patricia::element_t](/libpalliate/generated/Classes/structpatricia_1_1element__t)**

|                | Name           |
| -------------- | -------------- |
| [pkey_t](/libpalliate/generated/Files/patricia_8h#using-pkey-t) | **[mask](/libpalliate/generated/Classes/structpatricia_1_1element__t#function-mask)**() |
| | **[element_t](/libpalliate/generated/Classes/structpatricia_1_1element__t#function-element-t)**([pkey_t](/libpalliate/generated/Files/patricia_8h#using-pkey-t) _key, uint8_t _branchbit) |
| virtual | **[~element_t](/libpalliate/generated/Classes/structpatricia_1_1element__t#function-~element-t)**() |

**Public Attributes inherited from [patricia::element_t](/libpalliate/generated/Classes/structpatricia_1_1element__t)**

|                | Name           |
| -------------- | -------------- |
| [pkey_t](/libpalliate/generated/Files/patricia_8h#using-pkey-t) | **[key](/libpalliate/generated/Classes/structpatricia_1_1element__t#variable-key)**  |
| [node_t](/libpalliate/generated/Classes/structpatricia_1_1node__t) * | **[parent](/libpalliate/generated/Classes/structpatricia_1_1element__t#variable-parent)**  |
| uint8_t | **[branchbit](/libpalliate/generated/Classes/structpatricia_1_1element__t#variable-branchbit)**  |


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


**Reimplements**: [patricia::leaf_t::to_str](/libpalliate/generated/Classes/structpatricia_1_1leaf__t#function-to-str)


### function print

```cpp
virtual void print() override
```


**Reimplements**: [memory::element_t::print](/libpalliate/generated/Classes/structmemory_1_1element__t#function-print)


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



_Automatically updated on 2022-05-02 at 01:42:07 +0000._