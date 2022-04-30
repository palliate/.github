---
title: window

---

# window






`#include <window.h>`

## Public Types

|                | Name           |
| -------------- | -------------- |
| enum uint8_t | **[flag](Classes/classwindow.md#enum-flag)** { visible, minimized, maximized, focused, floating} |

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[window](Classes/classwindow.md#function-window)**() =default |
| virtual | **[~window](Classes/classwindow.md#function-~window)**() =default |
| virtual void | **[attention](Classes/classwindow.md#function-attention)**() =0 |
| void | **[set](Classes/classwindow.md#function-set)**([flag](Classes/classwindow.md#enum-flag) _flag, bool value =true) |
| virtual std::bitset< 8 > & | **[get_flags](Classes/classwindow.md#function-get-flags)**() |
| virtual void | **[resize](Classes/classwindow.md#function-resize)**(unsigned width, unsigned height) =0 |
| virtual void | **[move](Classes/classwindow.md#function-move)**(int x, int y) =0 |
| virtual void | **[title](Classes/classwindow.md#function-title)**(const std::string & title) =0 |
| virtual void | **[icon](Classes/classwindow.md#function-icon)**(unsigned height, unsigned width, const char * data) =0 |
| virtual void | **[wireframe](Classes/classwindow.md#function-wireframe)**(bool status) =0 |
| virtual bool | **[render](Classes/classwindow.md#function-render)**() =0 |

## Protected Functions

|                | Name           |
| -------------- | -------------- |
| virtual void | **[handle_flag](Classes/classwindow.md#function-handle-flag)**([flag](Classes/classwindow.md#enum-flag) _flag, bool value) =0 |

## Protected Attributes

|                | Name           |
| -------------- | -------------- |
| std::bitset< 8 > | **[flags](Classes/classwindow.md#variable-flags)**  |

## Public Types Documentation

### enum flag

| Enumerator | Value | Description |
| ---------- | ----- | ----------- |
| visible | |   |
| minimized | |   |
| maximized | |   |
| focused | |   |
| floating | |   |




## Public Functions Documentation

### function window

```cpp
window() =default
```


### function ~window

```cpp
virtual ~window() =default
```


### function attention

```cpp
virtual void attention() =0
```


### function set

```cpp
void set(
    flag _flag,
    bool value =true
)
```


### function get_flags

```cpp
virtual std::bitset< 8 > & get_flags()
```


### function resize

```cpp
virtual void resize(
    unsigned width,
    unsigned height
) =0
```


### function move

```cpp
virtual void move(
    int x,
    int y
) =0
```


### function title

```cpp
virtual void title(
    const std::string & title
) =0
```


### function icon

```cpp
virtual void icon(
    unsigned height,
    unsigned width,
    const char * data
) =0
```


### function wireframe

```cpp
virtual void wireframe(
    bool status
) =0
```


### function render

```cpp
virtual bool render() =0
```


## Protected Functions Documentation

### function handle_flag

```cpp
virtual void handle_flag(
    flag _flag,
    bool value
) =0
```


## Protected Attributes Documentation

### variable flags

```cpp
std::bitset< 8 > flags;
```


-------------------------------

Updated on 2022-04-30 at 06:56:37 +0000