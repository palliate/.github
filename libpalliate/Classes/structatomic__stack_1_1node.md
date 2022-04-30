---
title: atomic_stack::node

---

# atomic_stack::node






`#include <atomic_stack.h>`

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[node](Classes/structatomic__stack_1_1node.md#function-node)**(T && _data) |
| | **[~node](Classes/structatomic__stack_1_1node.md#function-~node)**() |

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| T | **[data](Classes/structatomic__stack_1_1node.md#variable-data)**  |
| [node](Classes/structatomic__stack_1_1node.md) * | **[next](Classes/structatomic__stack_1_1node.md#variable-next)**  |
| [node](Classes/structatomic__stack_1_1node.md) * | **[prev](Classes/structatomic__stack_1_1node.md#variable-prev)**  |

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


-------------------------------

Updated on 2022-04-30 at 06:56:37 +0000