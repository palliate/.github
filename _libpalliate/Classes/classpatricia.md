---
title: patricia

---

# patricia






`#include <patricia.h>`

## Public Classes

|                | Name           |
| -------------- | -------------- |
| struct | **[element_t](Classes/structpatricia_1_1element__t.md)**  |
| struct | **[leaf_t](Classes/structpatricia_1_1leaf__t.md)**  |
| struct | **[node_t](Classes/structpatricia_1_1node__t.md)**  |

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[patricia](Classes/classpatricia.md#function-patricia)**() =default |
| | **[~patricia](Classes/classpatricia.md#function-~patricia)**() |
| [leaf_t](Classes/structpatricia_1_1leaf__t.md) * | **[find_last](Classes/classpatricia.md#function-find-last)**([element_t](Classes/structpatricia_1_1element__t.md) * subtree) |
| [leaf_t](Classes/structpatricia_1_1leaf__t.md) * | **[find_first](Classes/classpatricia.md#function-find-first)**([element_t](Classes/structpatricia_1_1element__t.md) * subtree) |
| [leaf_t](Classes/structpatricia_1_1leaf__t.md) * | **[find_last](Classes/classpatricia.md#function-find-last)**() |
| [leaf_t](Classes/structpatricia_1_1leaf__t.md) * | **[find_first](Classes/classpatricia.md#function-find-first)**() |
| [leaf_t](Classes/structpatricia_1_1leaf__t.md) * | **[find](Classes/classpatricia.md#function-find)**([pkey_t](Files/patricia_8h.md#using-pkey-t) key) |
| template <class T \> <br>| **[requires](Classes/classpatricia.md#function-requires)**(std::derived_from< T, [patricia::leaf_t](Classes/structpatricia_1_1leaf__t.md) > ) |
| template <class T \> <br>| **[requires](Classes/classpatricia.md#function-requires)**(std::derived_from< T, [patricia::leaf_t](Classes/structpatricia_1_1leaf__t.md) > ) |
| void | **[remove](Classes/classpatricia.md#function-remove)**([pkey_t](Files/patricia_8h.md#using-pkey-t) key) |
| void | **[clear](Classes/classpatricia.md#function-clear)**() |
| void | **[print](Classes/classpatricia.md#function-print)**() |

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


### function requires

```cpp
template <class T >
requires(
    std::derived_from< T, patricia::leaf_t > 
)
```


### function requires

```cpp
template <class T >
requires(
    std::derived_from< T, patricia::leaf_t > 
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


-------------------------------

Updated on 2022-04-30 at 06:56:37 +0000