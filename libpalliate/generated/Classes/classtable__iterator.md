---
title: table_iterator
parent: Classes
grand_parent: libpalliate
layout: default
---

# table_iterator



 [More...](#detailed-description)


`#include <toml.hpp>`

## Public Types

|                | Name           |
| -------------- | -------------- |
| using table_proxy_pair< IsConst > | **[value_type](/libpalliate/generated/Classes/classtable__iterator#using-value-type)**  |
| using [value_type](/libpalliate/generated/Classes/classtable__iterator#using-value-type) & | **[reference](/libpalliate/generated/Classes/classtable__iterator#using-reference)**  |
| using [value_type](/libpalliate/generated/Classes/classtable__iterator#using-value-type) * | **[pointer](/libpalliate/generated/Classes/classtable__iterator#using-pointer)**  |
| using typename std::iterator_traits< map_iterator >::[difference_type](/libpalliate/generated/Classes/classtable__iterator#using-difference-type) | **[difference_type](/libpalliate/generated/Classes/classtable__iterator#using-difference-type)**  |
| using typename std::iterator_traits< map_iterator >::[iterator_category](/libpalliate/generated/Classes/classtable__iterator#using-iterator-category) | **[iterator_category](/libpalliate/generated/Classes/classtable__iterator#using-iterator-category)**  |

## Public Functions

|                | Name           |
| -------------- | -------------- |
| [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor) | **[table_iterator](/libpalliate/generated/Classes/classtable__iterator#function-table-iterator)**() =default |
| [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor) | **[table_iterator](/libpalliate/generated/Classes/classtable__iterator#function-table-iterator)**(mutable_map_iterator iter) |
| [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor) | **[table_iterator](/libpalliate/generated/Classes/classtable__iterator#function-table-iterator)**(const_map_iterator iter) |
| [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor) | **[table_iterator](/libpalliate/generated/Classes/classtable__iterator#function-table-iterator)**(const [table_iterator](/libpalliate/generated/Classes/classtable__iterator)< false > & other) |
| [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor) | **[table_iterator](/libpalliate/generated/Classes/classtable__iterator#function-table-iterator)**(const [table_iterator](/libpalliate/generated/Classes/classtable__iterator) & other) |
| [table_iterator](/libpalliate/generated/Classes/classtable__iterator) & | **[operator=](/libpalliate/generated/Classes/classtable__iterator#function-operator=)**(const [table_iterator](/libpalliate/generated/Classes/classtable__iterator) & rhs) |
| [table_iterator](/libpalliate/generated/Classes/classtable__iterator) & | **[operator++](/libpalliate/generated/Classes/classtable__iterator#function-operator++)**() |
| [table_iterator](/libpalliate/generated/Classes/classtable__iterator) | **[operator++](/libpalliate/generated/Classes/classtable__iterator#function-operator++)**(int ) |
| [table_iterator](/libpalliate/generated/Classes/classtable__iterator) & | **[operator--](/libpalliate/generated/Classes/classtable__iterator#function-operator--)**() |
| [table_iterator](/libpalliate/generated/Classes/classtable__iterator) | **[operator--](/libpalliate/generated/Classes/classtable__iterator#function-operator--)**(int ) |
| [TOML_PURE_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-inline-getter)[reference](/libpalliate/generated/Classes/classtable__iterator#using-reference) | **[operator*](/libpalliate/generated/Classes/classtable__iterator#function-operator*)**() const |
| [TOML_PURE_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-inline-getter)[pointer](/libpalliate/generated/Classes/classtable__iterator#using-pointer) | **[operator->](/libpalliate/generated/Classes/classtable__iterator#function-operator->)**() const |
| [TOML_PURE_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-inline-getter) | **[operator const map_iterator &](/libpalliate/generated/Classes/classtable__iterator#function-operator-const-map-iterator-&)**() const |
| [TOML_PURE_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-inline-getter) | **[operator const const_map_iterator](/libpalliate/generated/Classes/classtable__iterator#function-operator-const-const-map-iterator)**() const |

## Friends

|                | Name           |
| -------------- | -------------- |
| class | **[table_iterator](/libpalliate/generated/Classes/classtable__iterator#friend-table-iterator)**  |

## Detailed Description

```cpp
template <bool IsConst>
class table_iterator;
```

## Public Types Documentation

### using value_type

```cpp
using table_iterator< IsConst >::value_type =  table_proxy_pair<IsConst>;
```


### using reference

```cpp
using table_iterator< IsConst >::reference =  value_type&;
```


### using pointer

```cpp
using table_iterator< IsConst >::pointer =  value_type*;
```


### using difference_type

```cpp
using table_iterator< IsConst >::difference_type =  typename std::iterator_traits<map_iterator>::difference_type;
```


### using iterator_category

```cpp
using table_iterator< IsConst >::iterator_category =  typename std::iterator_traits<map_iterator>::iterator_category;
```


## Public Functions Documentation

### function table_iterator

```cpp
TOML_NODISCARD_CTOR table_iterator() =default
```


### function table_iterator

```cpp
inline explicit TOML_NODISCARD_CTOR table_iterator(
    mutable_map_iterator iter
)
```


### function table_iterator

```cpp
inline explicit TOML_NODISCARD_CTOR table_iterator(
    const_map_iterator iter
)
```


### function table_iterator

```cpp
inline TOML_NODISCARD_CTOR table_iterator(
    const table_iterator< false > & other
)
```


### function table_iterator

```cpp
inline TOML_NODISCARD_CTOR table_iterator(
    const table_iterator & other
)
```


### function operator=

```cpp
inline table_iterator & operator=(
    const table_iterator & rhs
)
```


### function operator++

```cpp
inline table_iterator & operator++()
```


### function operator++

```cpp
inline table_iterator operator++(
    int 
)
```


### function operator--

```cpp
inline table_iterator & operator--()
```


### function operator--

```cpp
inline table_iterator operator--(
    int 
)
```


### function operator*

```cpp
inline TOML_PURE_INLINE_GETTERreference operator*() const
```


### function operator->

```cpp
inline TOML_PURE_INLINE_GETTERpointer operator->() const
```


### function operator const map_iterator &

```cpp
inline explicit TOML_PURE_INLINE_GETTER operator const map_iterator &() const
```


### function operator const const_map_iterator

```cpp
inline explicit TOML_PURE_INLINE_GETTER operator const const_map_iterator() const
```


## Friends

### friend table_iterator

```cpp
friend class table_iterator;
```



_Automatically updated on 2022-05-02 at 01:42:11 +0000._