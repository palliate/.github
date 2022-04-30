---
title: config::parser::settings

---

# config::parser::settings






`#include <settings.h>`

Inherits from [config::parser::parser](Classes/classconfig_1_1parser_1_1parser.md)

## Public Functions

|                | Name           |
| -------------- | -------------- |
| void | **[set_defaults](Classes/classconfig_1_1parser_1_1settings.md#function-set-defaults)**(std::map< std::string_view, [setting](Classes/structconfig_1_1setting.md) > const & defaults) |
| void | **[parse](Classes/classconfig_1_1parser_1_1settings.md#function-parse)**(std::filesystem::path & config_path) |
| virtual [config::value_t](Namespaces/namespaceconfig.md#using-value-t) | **[get](Classes/classconfig_1_1parser_1_1settings.md#function-get)**(std::string const & opt) override |

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
    std::map< std::string_view, setting > const & defaults
)
```


### function parse

```cpp
void parse(
    std::filesystem::path & config_path
)
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