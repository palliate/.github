---
title: patricia::element_t
parent: Classes
grand_parent: libpalliate
layout: default
---

# patricia::element_t






`#include <patricia.h>`

Inherited by [patricia::leaf_t](/libpalliate/generated/Classes/structpatricia_1_1leaf__t), [patricia::node_t](/libpalliate/generated/Classes/structpatricia_1_1node__t)

## Public Functions

|                | Name           |
| -------------- | -------------- |
| [pkey_t](/libpalliate/generated/Files/patricia_8h#using-pkey-t) | **[mask](/libpalliate/generated/Classes/structpatricia_1_1element__t#function-mask)**() |
| | **[element_t](/libpalliate/generated/Classes/structpatricia_1_1element__t#function-element-t)**([pkey_t](/libpalliate/generated/Files/patricia_8h#using-pkey-t) _key, uint8_t _branchbit) |
| virtual | **[~element_t](/libpalliate/generated/Classes/structpatricia_1_1element__t#function-~element-t)**() |

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| [pkey_t](/libpalliate/generated/Files/patricia_8h#using-pkey-t) | **[key](/libpalliate/generated/Classes/structpatricia_1_1element__t#variable-key)**  |
| [node_t](/libpalliate/generated/Classes/structpatricia_1_1node__t) * | **[parent](/libpalliate/generated/Classes/structpatricia_1_1element__t#variable-parent)**  |
| uint8_t | **[branchbit](/libpalliate/generated/Classes/structpatricia_1_1element__t#variable-branchbit)**  |

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



_Automatically updated on 2022-05-07 at 23:35:51 +0000._