---
title: patricia::node_t

---

# patricia::node_t






`#include <patricia.h>`

Inherits from [patricia::element_t](Classes/structpatricia_1_1element__t.md)

## Public Functions

|                | Name           |
| -------------- | -------------- |
| bool | **[branch](Classes/structpatricia_1_1node__t.md#function-branch)**([pkey_t](Files/patricia_8h.md#using-pkey-t) key) |
| [element_t](Classes/structpatricia_1_1element__t.md) ** | **[next](Classes/structpatricia_1_1node__t.md#function-next)**([pkey_t](Files/patricia_8h.md#using-pkey-t) key) |
| [leaf_t](Classes/structpatricia_1_1leaf__t.md) * | **[traverse](Classes/structpatricia_1_1node__t.md#function-traverse)**(bool branch) |
| [leaf_t](Classes/structpatricia_1_1leaf__t.md) * | **[find_last](Classes/structpatricia_1_1node__t.md#function-find-last)**() |
| [leaf_t](Classes/structpatricia_1_1leaf__t.md) * | **[find_first](Classes/structpatricia_1_1node__t.md#function-find-first)**() |
| | **[node_t](Classes/structpatricia_1_1node__t.md#function-node-t)**([pkey_t](Files/patricia_8h.md#using-pkey-t) _key, unsigned _branchbit) |
| | **[~node_t](Classes/structpatricia_1_1node__t.md#function-~node-t)**() |

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| [element_t](Classes/structpatricia_1_1element__t.md) * | **[children](Classes/structpatricia_1_1node__t.md#variable-children)**  |

## Additional inherited members

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

### function branch

```cpp
inline bool branch(
    pkey_t key
)
```


### function next

```cpp
inline element_t ** next(
    pkey_t key
)
```


### function traverse

```cpp
leaf_t * traverse(
    bool branch
)
```


### function find_last

```cpp
inline leaf_t * find_last()
```


### function find_first

```cpp
inline leaf_t * find_first()
```


### function node_t

```cpp
inline node_t(
    pkey_t _key,
    unsigned _branchbit
)
```


### function ~node_t

```cpp
inline ~node_t()
```


## Public Attributes Documentation

### variable children

```cpp
element_t * children;
```


-------------------------------

Updated on 2022-04-30 at 06:56:37 +0000