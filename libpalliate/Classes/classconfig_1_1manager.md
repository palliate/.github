---
title: config::manager

---

# config::manager






`#include <manager.h>`

## Public Functions

|                | Name           |
| -------------- | -------------- |
| [manager](Classes/classconfig_1_1manager.md) & | **[Instance](Classes/classconfig_1_1manager.md#function-instance)**() |
| | **[manager](Classes/classconfig_1_1manager.md#function-manager)**([manager](Classes/classconfig_1_1manager.md) const & ) =delete |
| void | **[operator=](Classes/classconfig_1_1manager.md#function-operator=)**([manager](Classes/classconfig_1_1manager.md) const & ) =delete |
| | **[~manager](Classes/classconfig_1_1manager.md#function-~manager)**() =default |
| void | **[print](Classes/classconfig_1_1manager.md#function-print)**() const |
| template <typename T \> <br>T | **[get](Classes/classconfig_1_1manager.md#function-get)**(std::string const & opt) |
| bool | **[get_flag](Classes/classconfig_1_1manager.md#function-get-flag)**(std::string const & opt) |
| [config::value_t](Namespaces/namespaceconfig.md#using-value-t) | **[operator[]](Classes/classconfig_1_1manager.md#function-operator[])**(std::string const & opt) |

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| [parser::cli](Classes/classconfig_1_1parser_1_1cli.md) | **[cli](Classes/classconfig_1_1manager.md#variable-cli)**  |
| [parser::settings](Classes/classconfig_1_1parser_1_1settings.md) | **[settings](Classes/classconfig_1_1manager.md#variable-settings)**  |

## Public Functions Documentation

### function Instance

```cpp
static manager & Instance()
```


### function manager

```cpp
manager(
    manager const & 
) =delete
```


### function operator=

```cpp
void operator=(
    manager const & 
) =delete
```


### function ~manager

```cpp
~manager() =default
```


### function print

```cpp
void print() const
```


### function get

```cpp
template <typename T >
T get(
    std::string const & opt
)
```


### function get_flag

```cpp
bool get_flag(
    std::string const & opt
)
```


### function operator[]

```cpp
config::value_t operator[](
    std::string const & opt
)
```


## Public Attributes Documentation

### variable cli

```cpp
parser::cli cli;
```


### variable settings

```cpp
parser::settings settings;
```


-------------------------------

Updated on 2022-04-30 at 06:56:37 +0000