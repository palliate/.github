---
title: patricia::leaf_t
parent: Classes
grand_parent: libpalliate
layout: default
---

# patricia::leaf_t






`#include <patricia.h>`

Inherits from [patricia::element_t](/libpalliate/generated/Classes/structpatricia_1_1element__t)

Inherited by [memory::node_t](/libpalliate/generated/Classes/structmemory_1_1node__t)

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[leaf_t](/libpalliate/generated/Classes/structpatricia_1_1leaf__t#function-leaf-t)**([pkey_t](/libpalliate/generated/Files/patricia_8h#using-pkey-t) _key) |
| | **[~leaf_t](/libpalliate/generated/Classes/structpatricia_1_1leaf__t#function-~leaf-t)**() |
| [leaf_t](/libpalliate/generated/Classes/structpatricia_1_1leaf__t) * | **[find_next](/libpalliate/generated/Classes/structpatricia_1_1leaf__t#function-find-next)**() |
| [leaf_t](/libpalliate/generated/Classes/structpatricia_1_1leaf__t) * | **[find_prev](/libpalliate/generated/Classes/structpatricia_1_1leaf__t#function-find-prev)**() |
| virtual std::string | **[to_str](/libpalliate/generated/Classes/structpatricia_1_1leaf__t#function-to-str)**() =0 |

## Additional inherited members

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


**Reimplemented by**: [memory::node_t::to_str](/libpalliate/generated/Classes/structmemory_1_1node__t#function-to-str)



_Automatically updated on 2022-05-02 at 01:49:10 +0000._