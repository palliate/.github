---
title: patricia::node_t
parent: Classes
grand_parent: libpalliate
layout: default
---

# patricia::node_t






`#include <patricia.h>`

Inherits from [patricia::element_t](/libpalliate/generated/Classes/structpatricia_1_1element__t)

## Public Functions

|                | Name           |
| -------------- | -------------- |
| bool | **[branch](/libpalliate/generated/Classes/structpatricia_1_1node__t#function-branch)**([pkey_t](/libpalliate/generated/Files/patricia_8h#using-pkey-t) key) |
| [element_t](/libpalliate/generated/Classes/structpatricia_1_1element__t) ** | **[next](/libpalliate/generated/Classes/structpatricia_1_1node__t#function-next)**([pkey_t](/libpalliate/generated/Files/patricia_8h#using-pkey-t) key) |
| [leaf_t](/libpalliate/generated/Classes/structpatricia_1_1leaf__t) * | **[traverse](/libpalliate/generated/Classes/structpatricia_1_1node__t#function-traverse)**(bool branch) |
| [leaf_t](/libpalliate/generated/Classes/structpatricia_1_1leaf__t) * | **[find_last](/libpalliate/generated/Classes/structpatricia_1_1node__t#function-find-last)**() |
| [leaf_t](/libpalliate/generated/Classes/structpatricia_1_1leaf__t) * | **[find_first](/libpalliate/generated/Classes/structpatricia_1_1node__t#function-find-first)**() |
| | **[node_t](/libpalliate/generated/Classes/structpatricia_1_1node__t#function-node-t)**([pkey_t](/libpalliate/generated/Files/patricia_8h#using-pkey-t) _key, unsigned _branchbit) |
| | **[~node_t](/libpalliate/generated/Classes/structpatricia_1_1node__t#function-~node-t)**() |

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| [element_t](/libpalliate/generated/Classes/structpatricia_1_1element__t) * | **[children](/libpalliate/generated/Classes/structpatricia_1_1node__t#variable-children)**  |

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



_Automatically updated on 2022-05-07 at 23:06:39 +0000._