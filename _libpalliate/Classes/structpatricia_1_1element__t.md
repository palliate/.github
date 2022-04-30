---
title: patricia::element_t

---

# patricia::element_t






`#include <patricia.h>`

Inherited by [patricia::leaf_t](Classes/structpatricia_1_1leaf__t.md), [patricia::node_t](Classes/structpatricia_1_1node__t.md)

## Public Functions

|                | Name           |
| -------------- | -------------- |
| [pkey_t](Files/patricia_8h.md#using-pkey-t) | **[mask](Classes/structpatricia_1_1element__t.md#function-mask)**() |
| | **[element_t](Classes/structpatricia_1_1element__t.md#function-element-t)**([pkey_t](Files/patricia_8h.md#using-pkey-t) _key, uint8_t _branchbit) |
| virtual | **[~element_t](Classes/structpatricia_1_1element__t.md#function-~element-t)**() |

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| [pkey_t](Files/patricia_8h.md#using-pkey-t) | **[key](Classes/structpatricia_1_1element__t.md#variable-key)**  |
| [node_t](Classes/structpatricia_1_1node__t.md) * | **[parent](Classes/structpatricia_1_1element__t.md#variable-parent)**  |
| uint8_t | **[branchbit](Classes/structpatricia_1_1element__t.md#variable-branchbit)**  |

## Public Functions Documentation

### function mask

```cpp
pkey_t mask()
```


### function element_t

```cpp
inline element_t(
    pkey_t _key,
    uint8_t _branchbit
)
```


### function ~element_t

```cpp
inline virtual ~element_t()
```


## Public Attributes Documentation

### variable key

```cpp
pkey_t key = 0;
```


### variable parent

```cpp
node_t * parent = nullptr;
```


### variable branchbit

```cpp
uint8_t branchbit = 0;
```


-------------------------------

Updated on 2022-04-30 at 06:56:37 +0000