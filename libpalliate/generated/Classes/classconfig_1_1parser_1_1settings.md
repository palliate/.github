---
title: config::parser::settings
parent: Classes
grand_parent: libpalliate
layout: default
---

# config::parser::settings






`#include <settings.h>`

Inherits from [config::parser::parser](/libpalliate/generated/Classes/classconfig_1_1parser_1_1parser)

## Public Functions

|                | Name           |
| -------------- | -------------- |
| void | **[set_defaults](/libpalliate/generated/Classes/classconfig_1_1parser_1_1settings#function-set-defaults)**(std::map< std::string_view, [setting](/libpalliate/generated/Classes/structconfig_1_1setting) > const & defaults) |
| void | **[parse](/libpalliate/generated/Classes/classconfig_1_1parser_1_1settings#function-parse)**(std::filesystem::path & config_path) |
| virtual [config::value_t](/libpalliate/generated/Namespaces/namespaceconfig#using-value-t) | **[get](/libpalliate/generated/Classes/classconfig_1_1parser_1_1settings#function-get)**(std::string const & opt) override |

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


**Reimplements**: [config::parser::parser::get](/libpalliate/generated/Classes/classconfig_1_1parser_1_1parser#function-get)



_Automatically updated on 2022-05-02 at 01:49:10 +0000._