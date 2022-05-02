---
title: ui
parent: Classes
grand_parent: libpalliate
layout: default
---

# ui






`#include <ui.h>`

Inherits from [runnable](/libpalliate/generated/Classes/classrunnable)

## Public Functions

|                | Name           |
| -------------- | -------------- |
| [ui](/libpalliate/generated/Classes/classui) & | **[Instance](/libpalliate/generated/Classes/classui#function-instance)**() |
| void | **[toggle_fullscreen](/libpalliate/generated/Classes/classui#function-toggle-fullscreen)**() |
| | **[ui](/libpalliate/generated/Classes/classui#function-ui)**([ui](/libpalliate/generated/Classes/classui) const & ) =delete |
| void | **[operator=](/libpalliate/generated/Classes/classui#function-operator=)**([ui](/libpalliate/generated/Classes/classui) const & ) =delete |
| | **[~ui](/libpalliate/generated/Classes/classui#function-~ui)**() |
| template <class T ,typename... Args\> <br>| **[requires](/libpalliate/generated/Classes/classui#function-requires)**(std::derived_from< T, [backend](/libpalliate/generated/Classes/classbackend) > ) |

## Additional inherited members

**Public Types inherited from [runnable](/libpalliate/generated/Classes/classrunnable)**

|                | Name           |
| -------------- | -------------- |
| using std::function< void()> | **[callback_f](/libpalliate/generated/Classes/classrunnable#using-callback-f)**  |
| using std::stop_callback< [callback_f](/libpalliate/generated/Classes/classrunnable#using-callback-f) > | **[callback_t](/libpalliate/generated/Classes/classrunnable#using-callback-t)**  |

**Public Functions inherited from [runnable](/libpalliate/generated/Classes/classrunnable)**

|                | Name           |
| -------------- | -------------- |
| | **[runnable](/libpalliate/generated/Classes/classrunnable#function-runnable)**(std::string const & _name) |
| virtual | **[~runnable](/libpalliate/generated/Classes/classrunnable#function-~runnable)**() |
| virtual void | **[operator()](/libpalliate/generated/Classes/classrunnable#function-operator())**(std::stop_token token ={}) |
| void | **[run](/libpalliate/generated/Classes/classrunnable#function-run)**() |
| void | **[run](/libpalliate/generated/Classes/classrunnable#function-run)**([callback_f](/libpalliate/generated/Classes/classrunnable#using-callback-f) _callback) |
| void | **[stop](/libpalliate/generated/Classes/classrunnable#function-stop)**() |
| auto | **[operator](/libpalliate/generated/Classes/classrunnable#function-operator)**([runnable](/libpalliate/generated/Classes/classrunnable) const & other) const |

**Protected Attributes inherited from [runnable](/libpalliate/generated/Classes/classrunnable)**

|                | Name           |
| -------------- | -------------- |
| std::jthread | **[thread](/libpalliate/generated/Classes/classrunnable#variable-thread)**  |
| std::unique_ptr< [callback_t](/libpalliate/generated/Classes/classrunnable#using-callback-t) > | **[callback](/libpalliate/generated/Classes/classrunnable#variable-callback)**  |
| const std::string | **[name](/libpalliate/generated/Classes/classrunnable#variable-name)**  |


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



_Automatically updated on 2022-05-02 at 01:49:09 +0000._