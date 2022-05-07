---
title: patricia
parent: Classes
grand_parent: libpalliate
layout: default
---

# patricia






`#include <patricia.h>`

## Public Classes

|                | Name           |
| -------------- | -------------- |
| struct | **[element_t](/libpalliate/generated/Classes/structpatricia_1_1element__t)**  |
| struct | **[leaf_t](/libpalliate/generated/Classes/structpatricia_1_1leaf__t)**  |
| struct | **[node_t](/libpalliate/generated/Classes/structpatricia_1_1node__t)**  |

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[patricia](/libpalliate/generated/Classes/classpatricia#function-patricia)**() =default |
| | **[~patricia](/libpalliate/generated/Classes/classpatricia#function-~patricia)**() |
| [leaf_t](/libpalliate/generated/Classes/structpatricia_1_1leaf__t) * | **[find_last](/libpalliate/generated/Classes/classpatricia#function-find-last)**([element_t](/libpalliate/generated/Classes/structpatricia_1_1element__t) * subtree) |
| [leaf_t](/libpalliate/generated/Classes/structpatricia_1_1leaf__t) * | **[find_first](/libpalliate/generated/Classes/classpatricia#function-find-first)**([element_t](/libpalliate/generated/Classes/structpatricia_1_1element__t) * subtree) |
| [leaf_t](/libpalliate/generated/Classes/structpatricia_1_1leaf__t) * | **[find_last](/libpalliate/generated/Classes/classpatricia#function-find-last)**() |
| [leaf_t](/libpalliate/generated/Classes/structpatricia_1_1leaf__t) * | **[find_first](/libpalliate/generated/Classes/classpatricia#function-find-first)**() |
| [leaf_t](/libpalliate/generated/Classes/structpatricia_1_1leaf__t) * | **[find](/libpalliate/generated/Classes/classpatricia#function-find)**([pkey_t](/libpalliate/generated/Files/patricia_8h#using-pkey-t) key) |
| template <class T \> <br>bool | **[insert](/libpalliate/generated/Classes/classpatricia#function-insert)**(T * value) |
| template <class T \> <br>void | **[remove](/libpalliate/generated/Classes/classpatricia#function-remove)**(T * value) |
| void | **[remove](/libpalliate/generated/Classes/classpatricia#function-remove)**([pkey_t](/libpalliate/generated/Files/patricia_8h#using-pkey-t) key) |
| void | **[clear](/libpalliate/generated/Classes/classpatricia#function-clear)**() |
| void | **[print](/libpalliate/generated/Classes/classpatricia#function-print)**() |

## Public Functions Documentation

### function patricia

```cpp
patricia() =default
```


### function ~patricia

```cpp
inline ~patricia()
```


### function find_last

```cpp
inline leaf_t * find_last(
    element_t * subtree
)
```


### function find_first

```cpp
inline leaf_t * find_first(
    element_t * subtree
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


### function find

```cpp
leaf_t * find(
    pkey_t key
)
```


### function insert

```cpp
template <class T >
bool insert(
    T * value
)
```


### function remove

```cpp
template <class T >
void remove(
    T * value
)
```


### function remove

```cpp
void remove(
    pkey_t key
)
```


### function clear

```cpp
void clear()
```


### function print

```cpp
void print()
```



_Automatically updated on 2022-05-07 at 23:35:51 +0000._