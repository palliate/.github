---
title: atomic_stack
parent: Classes
grand_parent: libpalliate
layout: default
---

# atomic_stack



 [More...](#detailed-description)


`#include <atomic_stack.h>`

## Public Classes

|                | Name           |
| -------------- | -------------- |
| struct | **[node](/libpalliate/generated/Classes/structatomic__stack_1_1node)**  |

## Public Functions

|                | Name           |
| -------------- | -------------- |
| void | **[push](/libpalliate/generated/Classes/classatomic__stack#function-push)**(T && data) |
| std::tuple< [node](/libpalliate/generated/Classes/structatomic__stack_1_1node) *, [node](/libpalliate/generated/Classes/structatomic__stack_1_1node) * > | **[pop](/libpalliate/generated/Classes/classatomic__stack#function-pop)**(void ) |

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



_Automatically updated on 2022-05-07 at 23:06:39 +0000._