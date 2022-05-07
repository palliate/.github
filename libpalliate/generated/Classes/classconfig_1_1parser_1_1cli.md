---
title: config::parser::cli
parent: Classes
grand_parent: libpalliate
layout: default
---

# config::parser::cli






`#include <cli.h>`

Inherits from [config::parser::parser](/libpalliate/generated/Classes/classconfig_1_1parser_1_1parser)

## Public Functions

|                | Name           |
| -------------- | -------------- |
| void | **[set_defaults](/libpalliate/generated/Classes/classconfig_1_1parser_1_1cli#function-set-defaults)**(std::map< std::string_view, [cli_option](/libpalliate/generated/Classes/structconfig_1_1cli__option) > const & _defaults) |
| void | **[parse](/libpalliate/generated/Classes/classconfig_1_1parser_1_1cli#function-parse)**(int argc, char * argv[]) |
| std::string | **[help](/libpalliate/generated/Classes/classconfig_1_1parser_1_1cli#function-help)**() const |
| virtual [config::value_t](/libpalliate/generated/Namespaces/namespaceconfig#using-value-t) | **[get](/libpalliate/generated/Classes/classconfig_1_1parser_1_1cli#function-get)**(std::string const & opt) override |

## Additional inherited members

**Public Functions inherited from [config::parser::parser](/libpalliate/generated/Classes/classconfig_1_1parser_1_1parser)**

|                | Name           |
| -------------- | -------------- |
| virtual | **[~parser](/libpalliate/generated/Classes/classconfig_1_1parser_1_1parser#function-~parser)**() |
| void | **[print](/libpalliate/generated/Classes/classconfig_1_1parser_1_1parser#function-print)**() const |

**Protected Attributes inherited from [config::parser::parser](/libpalliate/generated/Classes/classconfig_1_1parser_1_1parser)**

|                | Name           |
| -------------- | -------------- |
| std::map< std::string, [config::value_t](/libpalliate/generated/Namespaces/namespaceconfig#using-value-t) > | **[options](/libpalliate/generated/Classes/classconfig_1_1parser_1_1parser#variable-options)**  |


## Public Functions Documentation

### function set_defaults

```cpp
void set_defaults(
    std::map< std::string_view, cli_option > const & _defaults
)
```


### function parse

```cpp
void parse(
    int argc,
    char * argv[]
)
```


### function help

```cpp
std::string help() const
```


### function get

```cpp
virtual config::value_t get(
    std::string const & opt
) override
```


**Reimplements**: [config::parser::parser::get](/libpalliate/generated/Classes/classconfig_1_1parser_1_1parser#function-get)



_Automatically updated on 2022-05-07 at 23:14:50 +0000._