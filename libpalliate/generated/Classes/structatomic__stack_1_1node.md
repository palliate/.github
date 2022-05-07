---
title: atomic_stack::node
parent: Classes
grand_parent: libpalliate
layout: default
---

# atomic_stack::node






`#include <atomic_stack.h>`

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[node](/libpalliate/generated/Classes/structatomic__stack_1_1node#function-node)**(T && _data) |
| | **[~node](/libpalliate/generated/Classes/structatomic__stack_1_1node#function-~node)**() |

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| T | **[data](/libpalliate/generated/Classes/structatomic__stack_1_1node#variable-data)**  |
| [node](/libpalliate/generated/Classes/structatomic__stack_1_1node) * | **[next](/libpalliate/generated/Classes/structatomic__stack_1_1node#variable-next)**  |
| [node](/libpalliate/generated/Classes/structatomic__stack_1_1node) * | **[prev](/libpalliate/generated/Classes/structatomic__stack_1_1node#variable-prev)**  |

## Public Functions Documentation

### function node

```cpp
inline explicit node(
    T && _data
)
```


### function ~node

```cpp
inline ~node()
```


## Public Attributes Documentation

### variable data

```cpp
T data;
```


### variable next

```cpp
node * next = nullptr;
```


### variable prev

```cpp
node * prev = nullptr;
```



_Automatically updated on 2022-05-07 at 23:35:51 +0000._