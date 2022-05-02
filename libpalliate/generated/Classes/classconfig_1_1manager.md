---
title: config::manager
parent: Classes
grand_parent: libpalliate
layout: default
---

# config::manager






`#include <manager.h>`

## Public Functions

|                | Name           |
| -------------- | -------------- |
| [manager](/libpalliate/generated/Classes/classconfig_1_1manager) & | **[Instance](/libpalliate/generated/Classes/classconfig_1_1manager#function-instance)**() |
| | **[manager](/libpalliate/generated/Classes/classconfig_1_1manager#function-manager)**([manager](/libpalliate/generated/Classes/classconfig_1_1manager) const & ) =delete |
| void | **[operator=](/libpalliate/generated/Classes/classconfig_1_1manager#function-operator=)**([manager](/libpalliate/generated/Classes/classconfig_1_1manager) const & ) =delete |
| | **[~manager](/libpalliate/generated/Classes/classconfig_1_1manager#function-~manager)**() =default |
| void | **[print](/libpalliate/generated/Classes/classconfig_1_1manager#function-print)**() const |
| template <typename T \> <br>T | **[get](/libpalliate/generated/Classes/classconfig_1_1manager#function-get)**(std::string const & opt) |
| bool | **[get_flag](/libpalliate/generated/Classes/classconfig_1_1manager#function-get-flag)**(std::string const & opt) |
| [config::value_t](/libpalliate/generated/Namespaces/namespaceconfig#using-value-t) | **[operator[]](/libpalliate/generated/Classes/classconfig_1_1manager#function-operator[])**(std::string const & opt) |

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| [parser::cli](/libpalliate/generated/Classes/classconfig_1_1parser_1_1cli) | **[cli](/libpalliate/generated/Classes/classconfig_1_1manager#variable-cli)**  |
| [parser::settings](/libpalliate/generated/Classes/classconfig_1_1parser_1_1settings) | **[settings](/libpalliate/generated/Classes/classconfig_1_1manager#variable-settings)**  |

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



_Automatically updated on 2022-05-02 at 01:42:11 +0000._