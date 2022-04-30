---
title: config::parser::cli

---

# config::parser::cli






`#include <cli.h>`

Inherits from [config::parser::parser](Classes/classconfig_1_1parser_1_1parser.md)

## Public Functions

|                | Name           |
| -------------- | -------------- |
| void | **[set_defaults](Classes/classconfig_1_1parser_1_1cli.md#function-set-defaults)**(std::map< std::string_view, [cli_option](Classes/structconfig_1_1cli__option.md) > const & _defaults) |
| void | **[parse](Classes/classconfig_1_1parser_1_1cli.md#function-parse)**(int argc, char * argv[]) |
| std::string | **[help](Classes/classconfig_1_1parser_1_1cli.md#function-help)**() const |
| virtual [config::value_t](Namespaces/namespaceconfig.md#using-value-t) | **[get](Classes/classconfig_1_1parser_1_1cli.md#function-get)**(std::string const & opt) override |

## Additional inherited members

**Public Functions inherited from [config::parser::parser](Classes/classconfig_1_1parser_1_1parser.md)**

|                | Name           |
| -------------- | -------------- |
| virtual | **[~parser](Classes/classconfig_1_1parser_1_1parser.md#function-~parser)**() |
| void | **[print](Classes/classconfig_1_1parser_1_1parser.md#function-print)**() const |

**Protected Attributes inherited from [config::parser::parser](Classes/classconfig_1_1parser_1_1parser.md)**

|                | Name           |
| -------------- | -------------- |
| std::map< std::string, [config::value_t](Namespaces/namespaceconfig.md#using-value-t) > | **[options](Classes/classconfig_1_1parser_1_1parser.md#variable-options)**  |


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


**Reimplements**: [config::parser::parser::get](Classes/classconfig_1_1parser_1_1parser.md#function-get)


-------------------------------

Updated on 2022-04-30 at 06:56:37 +0000