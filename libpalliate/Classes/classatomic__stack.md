---
title: atomic_stack

---

# atomic_stack



 [More...](#detailed-description)


`#include <atomic_stack.h>`

## Public Classes

|                | Name           |
| -------------- | -------------- |
| struct | **[node](Classes/structatomic__stack_1_1node.md)**  |

## Public Functions

|                | Name           |
| -------------- | -------------- |
| void | **[push](Classes/classatomic__stack.md#function-push)**(T && data) |
| std::tuple< [node](Classes/structatomic__stack_1_1node.md) *, [node](Classes/structatomic__stack_1_1node.md) * > | **[pop](Classes/classatomic__stack.md#function-pop)**(void ) |

## Detailed Description

```cpp
template <typename T >
class atomic_stack;
```

## Public Functions Documentation

### function push

```cpp
inline void push(
    T && data
)
```


### function pop

```cpp
inline std::tuple< node *, node * > pop(
    void 
)
```


-------------------------------

Updated on 2022-04-30 at 06:56:37 +0000