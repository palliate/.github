---
title: ui

---

# ui






`#include <ui.h>`

Inherits from [runnable](Classes/classrunnable.md)

## Public Functions

|                | Name           |
| -------------- | -------------- |
| [ui](Classes/classui.md) & | **[Instance](Classes/classui.md#function-instance)**() |
| void | **[toggle_fullscreen](Classes/classui.md#function-toggle-fullscreen)**() |
| | **[ui](Classes/classui.md#function-ui)**([ui](Classes/classui.md) const & ) =delete |
| void | **[operator=](Classes/classui.md#function-operator=)**([ui](Classes/classui.md) const & ) =delete |
| | **[~ui](Classes/classui.md#function-~ui)**() |
| template <class T ,typename... Args\> <br>| **[requires](Classes/classui.md#function-requires)**(std::derived_from< T, [backend](Classes/classbackend.md) > ) |

## Additional inherited members

**Public Types inherited from [runnable](Classes/classrunnable.md)**

|                | Name           |
| -------------- | -------------- |
| using std::function< void()> | **[callback_f](Classes/classrunnable.md#using-callback-f)**  |
| using std::stop_callback< [callback_f](Classes/classrunnable.md#using-callback-f) > | **[callback_t](Classes/classrunnable.md#using-callback-t)**  |

**Public Functions inherited from [runnable](Classes/classrunnable.md)**

|                | Name           |
| -------------- | -------------- |
| | **[runnable](Classes/classrunnable.md#function-runnable)**(std::string const & _name) |
| virtual | **[~runnable](Classes/classrunnable.md#function-~runnable)**() |
| virtual void | **[operator()](Classes/classrunnable.md#function-operator())**(std::stop_token token ={}) |
| void | **[run](Classes/classrunnable.md#function-run)**() |
| void | **[run](Classes/classrunnable.md#function-run)**([callback_f](Classes/classrunnable.md#using-callback-f) _callback) |
| void | **[stop](Classes/classrunnable.md#function-stop)**() |
| auto | **[operator](Classes/classrunnable.md#function-operator)**([runnable](Classes/classrunnable.md) const & other) const |

**Protected Attributes inherited from [runnable](Classes/classrunnable.md)**

|                | Name           |
| -------------- | -------------- |
| std::jthread | **[thread](Classes/classrunnable.md#variable-thread)**  |
| std::unique_ptr< [callback_t](Classes/classrunnable.md#using-callback-t) > | **[callback](Classes/classrunnable.md#variable-callback)**  |
| const std::string | **[name](Classes/classrunnable.md#variable-name)**  |


## Public Functions Documentation

### function Instance

```cpp
static ui & Instance()
```


### function toggle_fullscreen

```cpp
static void toggle_fullscreen()
```


### function ui

```cpp
ui(
    ui const & 
) =delete
```


### function operator=

```cpp
void operator=(
    ui const & 
) =delete
```


### function ~ui

```cpp
~ui()
```


### function requires

```cpp
template <class T ,
typename... Args>
requires(
    std::derived_from< T, backend > 
)
```


-------------------------------

Updated on 2022-04-30 at 06:56:37 +0000