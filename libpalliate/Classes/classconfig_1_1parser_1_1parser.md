---
title: config::parser::parser

---

# config::parser::parser






`#include <parser.h>`

Inherited by [config::parser::cli](Classes/classconfig_1_1parser_1_1cli.md), [config::parser::settings](Classes/classconfig_1_1parser_1_1settings.md)

## Public Functions

|                | Name           |
| -------------- | -------------- |
| virtual | **[~parser](Classes/classconfig_1_1parser_1_1parser.md#function-~parser)**() |
| virtual [config::value_t](Namespaces/namespaceconfig.md#using-value-t) | **[get](Classes/classconfig_1_1parser_1_1parser.md#function-get)**(std::string const & opt) =0 |
| void | **[print](Classes/classconfig_1_1parser_1_1parser.md#function-print)**() const |

## Protected Attributes

|                | Name           |
| -------------- | -------------- |
| std::map< std::string, [config::value_t](Namespaces/namespaceconfig.md#using-value-t) > | **[options](Classes/classconfig_1_1parser_1_1parser.md#variable-options)**  |

## Public Functions Documentation

### function ~parser

```cpp
inline virtual ~parser()
```


### function get

```cpp
virtual config::value_t get(
    std::string const & opt
) =0
```


**Reimplemented by**: [config::parser::settings::get](Classes/classconfig_1_1parser_1_1settings.md#function-get), [config::parser::cli::get](Classes/classconfig_1_1parser_1_1cli.md#function-get)


### function print

```cpp
void print() const
```


## Protected Attributes Documentation

### variable options

```cpp
std::map< std::string, config::value_t > options;
```


-------------------------------

Updated on 2022-04-30 at 06:56:37 +0000