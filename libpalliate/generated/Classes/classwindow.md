---
title: window
parent: Classes
grand_parent: libpalliate
layout: default
---

# window






`#include <window.h>`

## Public Types

|                | Name           |
| -------------- | -------------- |
| enum uint8_t | **[flag](/libpalliate/generated/Classes/classwindow#enum-flag)** { visible, minimized, maximized, focused, floating} |

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[window](/libpalliate/generated/Classes/classwindow#function-window)**() =default |
| virtual | **[~window](/libpalliate/generated/Classes/classwindow#function-~window)**() =default |
| virtual void | **[attention](/libpalliate/generated/Classes/classwindow#function-attention)**() =0 |
| void | **[set](/libpalliate/generated/Classes/classwindow#function-set)**([flag](/libpalliate/generated/Classes/classwindow#enum-flag) _flag, bool value =true) |
| virtual std::bitset< 8 > & | **[get_flags](/libpalliate/generated/Classes/classwindow#function-get-flags)**() |
| virtual void | **[resize](/libpalliate/generated/Classes/classwindow#function-resize)**(unsigned width, unsigned height) =0 |
| virtual void | **[move](/libpalliate/generated/Classes/classwindow#function-move)**(int x, int y) =0 |
| virtual void | **[title](/libpalliate/generated/Classes/classwindow#function-title)**(const std::string & title) =0 |
| virtual void | **[icon](/libpalliate/generated/Classes/classwindow#function-icon)**(unsigned height, unsigned width, const char * data) =0 |
| virtual void | **[wireframe](/libpalliate/generated/Classes/classwindow#function-wireframe)**(bool status) =0 |
| virtual bool | **[render](/libpalliate/generated/Classes/classwindow#function-render)**() =0 |

## Protected Functions

|                | Name           |
| -------------- | -------------- |
| virtual void | **[handle_flag](/libpalliate/generated/Classes/classwindow#function-handle-flag)**([flag](/libpalliate/generated/Classes/classwindow#enum-flag) _flag, bool value) =0 |

## Protected Attributes

|                | Name           |
| -------------- | -------------- |
| std::bitset< 8 > | **[flags](/libpalliate/generated/Classes/classwindow#variable-flags)**  |

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



_Automatically updated on 2022-05-02 at 01:49:09 +0000._