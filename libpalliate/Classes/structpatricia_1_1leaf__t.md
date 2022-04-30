---
title: patricia::leaf_t

---

# patricia::leaf_t






`#include <patricia.h>`

Inherits from [patricia::element_t](Classes/structpatricia_1_1element__t.md)

Inherited by [memory::node_t](Classes/structmemory_1_1node__t.md)

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[leaf_t](Classes/structpatricia_1_1leaf__t.md#function-leaf-t)**([pkey_t](Files/patricia_8h.md#using-pkey-t) _key) |
| | **[~leaf_t](Classes/structpatricia_1_1leaf__t.md#function-~leaf-t)**() |
| [leaf_t](Classes/structpatricia_1_1leaf__t.md) * | **[find_next](Classes/structpatricia_1_1leaf__t.md#function-find-next)**() |
| [leaf_t](Classes/structpatricia_1_1leaf__t.md) * | **[find_prev](Classes/structpatricia_1_1leaf__t.md#function-find-prev)**() |
| virtual std::string | **[to_str](Classes/structpatricia_1_1leaf__t.md#function-to-str)**() =0 |

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

### function leaf_t

```cpp
inline leaf_t(
    pkey_t _key
)
```


### function ~leaf_t

```cpp
inline ~leaf_t()
```


### function find_next

```cpp
inline leaf_t * find_next()
```


### function find_prev

```cpp
inline leaf_t * find_prev()
```


### function to_str

```cpp
virtual std::string to_str() =0
```


**Reimplemented by**: [memory::node_t::to_str](Classes/structmemory_1_1node__t.md#function-to-str)


-------------------------------

Updated on 2022-04-30 at 06:56:37 +0000