---
title: config::parser::parser
parent: Classes
grand_parent: libpalliate
layout: default
---

# config::parser::parser






`#include <parser.h>`

Inherited by [config::parser::cli](/libpalliate/generated/Classes/classconfig_1_1parser_1_1cli), [config::parser::settings](/libpalliate/generated/Classes/classconfig_1_1parser_1_1settings)

## Public Functions

|                | Name           |
| -------------- | -------------- |
| virtual | **[~parser](/libpalliate/generated/Classes/classconfig_1_1parser_1_1parser#function-~parser)**() |
| virtual [config::value_t](/libpalliate/generated/Namespaces/namespaceconfig#using-value-t) | **[get](/libpalliate/generated/Classes/classconfig_1_1parser_1_1parser#function-get)**(std::string const & opt) =0 |
| void | **[print](/libpalliate/generated/Classes/classconfig_1_1parser_1_1parser#function-print)**() const |

## Protected Attributes

|                | Name           |
| -------------- | -------------- |
| std::map< std::string, [config::value_t](/libpalliate/generated/Namespaces/namespaceconfig#using-value-t) > | **[options](/libpalliate/generated/Classes/classconfig_1_1parser_1_1parser#variable-options)**  |

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


**Reimplemented by**: [config::parser::settings::get](/libpalliate/generated/Classes/classconfig_1_1parser_1_1settings#function-get), [config::parser::cli::get](/libpalliate/generated/Classes/classconfig_1_1parser_1_1cli#function-get)


### function print

```cpp
void print() const
```


## Protected Attributes Documentation

### variable options

```cpp
std::map< std::string, config::value_t > options;
```



_Automatically updated on 2022-05-07 at 23:14:50 +0000._