---
title: atomic_mpsc

---

# atomic_mpsc






`#include <atomic_mpsc.h>`

## Public Classes

|                | Name           |
| -------------- | -------------- |
| struct | **[element](Classes/structatomic__mpsc_1_1element.md)**  |

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[atomic_mpsc](Classes/classatomic__mpsc.md#function-atomic-mpsc)**(unsigned _size, std::atomic< unsigned > * _freeList, std::atomic< unsigned > * _processList, [element](Classes/structatomic__mpsc_1_1element.md) * _list) |
| [element](Classes/structatomic__mpsc_1_1element.md) * | **[push](Classes/classatomic__mpsc.md#function-push)**(unsigned data) |
| [element](Classes/structatomic__mpsc_1_1element.md) * | **[pop](Classes/classatomic__mpsc.md#function-pop)**() |
| void | **[clear](Classes/classatomic__mpsc.md#function-clear)**([element](Classes/structatomic__mpsc_1_1element.md) * e) |
| unsigned | **[get_count](Classes/classatomic__mpsc.md#function-get-count)**() |

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| thread_local unsigned | **[tail](Classes/classatomic__mpsc.md#variable-tail)**  |

## Public Functions Documentation

### function atomic_mpsc

```cpp
inline atomic_mpsc(
    unsigned _size,
    std::atomic< unsigned > * _freeList,
    std::atomic< unsigned > * _processList,
    element * _list
)
```


### function push

```cpp
inline element * push(
    unsigned data
)
```


### function pop

```cpp
inline element * pop()
```


### function clear

```cpp
inline void clear(
    element * e
)
```


### function get_count

```cpp
inline unsigned get_count()
```


## Public Attributes Documentation

### variable tail

```cpp
static thread_local unsigned tail = 0;
```


-------------------------------

Updated on 2022-04-30 at 06:56:37 +0000