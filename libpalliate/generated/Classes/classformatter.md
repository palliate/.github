---
title: formatter
parent: Classes
grand_parent: libpalliate
layout: default
---

# formatter






`#include <toml.hpp>`

## Protected Functions

|                | Name           |
| -------------- | -------------- |
| const [TOML_PURE_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-inline-getter) node & | **[source](/libpalliate/generated/Classes/classformatter#function-source)**() const |
| [TOML_PURE_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-inline-getter) std::ostream & | **[stream](/libpalliate/generated/Classes/classformatter#function-stream)**() const |
| [TOML_PURE_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-inline-getter) int | **[indent](/libpalliate/generated/Classes/classformatter#function-indent)**() const |
| void | **[indent](/libpalliate/generated/Classes/classformatter#function-indent)**(int level) |
| void | **[increase_indent](/libpalliate/generated/Classes/classformatter#function-increase-indent)**() |
| void | **[decrease_indent](/libpalliate/generated/Classes/classformatter#function-decrease-indent)**() |
| [TOML_PURE_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-inline-getter) size_t | **[indent_columns](/libpalliate/generated/Classes/classformatter#function-indent-columns)**() const |
| [TOML_PURE_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-inline-getter) bool | **[indent_array_elements](/libpalliate/generated/Classes/classformatter#function-indent-array-elements)**() const |
| [TOML_PURE_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-inline-getter) bool | **[indent_sub_tables](/libpalliate/generated/Classes/classformatter#function-indent-sub-tables)**() const |
| [TOML_PURE_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-inline-getter) bool | **[literal_strings_allowed](/libpalliate/generated/Classes/classformatter#function-literal-strings-allowed)**() const |
| [TOML_PURE_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-inline-getter) bool | **[multi_line_strings_allowed](/libpalliate/generated/Classes/classformatter#function-multi-line-strings-allowed)**() const |
| [TOML_PURE_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-inline-getter) bool | **[real_tabs_in_strings_allowed](/libpalliate/generated/Classes/classformatter#function-real-tabs-in-strings-allowed)**() const |
| [TOML_PURE_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-inline-getter) bool | **[unicode_strings_allowed](/libpalliate/generated/Classes/classformatter#function-unicode-strings-allowed)**() const |
| [TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) void | **[attach](/libpalliate/generated/Classes/classformatter#function-attach)**(std::ostream & stream) |
| [TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) void | **[detach](/libpalliate/generated/Classes/classformatter#function-detach)**() |
| [TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) void | **[print_newline](/libpalliate/generated/Classes/classformatter#function-print-newline)**(bool force =false) |
| [TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) void | **[print_indent](/libpalliate/generated/Classes/classformatter#function-print-indent)**() |
| [TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) void | **[print_unformatted](/libpalliate/generated/Classes/classformatter#function-print-unformatted)**(char c) |
| [TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) void | **[print_unformatted](/libpalliate/generated/Classes/classformatter#function-print-unformatted)**(std::string_view str) |
| [TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) void | **[print_string](/libpalliate/generated/Classes/classformatter#function-print-string)**(std::string_view str, bool allow_multi_line =true, bool allow_bare =false) |
| [TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) void | **[print](/libpalliate/generated/Classes/classformatter#function-print)**(const [value](/libpalliate/generated/Classes/classvalue)< std::string > & val) |
| [TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) void | **[print](/libpalliate/generated/Classes/classformatter#function-print)**(const [value](/libpalliate/generated/Classes/classvalue)< int64_t > & val) |
| [TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) void | **[print](/libpalliate/generated/Classes/classformatter#function-print)**(const [value](/libpalliate/generated/Classes/classvalue)< double > & val) |
| [TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) void | **[print](/libpalliate/generated/Classes/classformatter#function-print)**(const [value](/libpalliate/generated/Classes/classvalue)< bool > & val) |
| [TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) void | **[print](/libpalliate/generated/Classes/classformatter#function-print)**(const [value](/libpalliate/generated/Classes/classvalue)< date > & val) |
| [TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) void | **[print](/libpalliate/generated/Classes/classformatter#function-print)**(const [value](/libpalliate/generated/Classes/classvalue)< [time](/libpalliate/generated/Classes/structtime) > & val) |
| [TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) void | **[print](/libpalliate/generated/Classes/classformatter#function-print)**(const [value](/libpalliate/generated/Classes/classvalue)< [date_time](/libpalliate/generated/Classes/structdate__time) > & val) |
| [TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) void | **[print_value](/libpalliate/generated/Classes/classformatter#function-print-value)**(const node & val_node, node_type type) |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) bool | **[dump_failed_parse_result](/libpalliate/generated/Classes/classformatter#function-dump-failed-parse-result)**() |
| [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor)[TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) | **[formatter](/libpalliate/generated/Classes/classformatter#function-formatter)**(const node * source_node, const [parse_result](/libpalliate/generated/Classes/classparse__result) * source_pr, const formatter_constants & constants, const [formatter_config](/libpalliate/generated/Classes/structformatter__config) & config) |

## Protected Functions Documentation

### function source

```cpp
inline const TOML_PURE_INLINE_GETTER node & source() const
```


### function stream

```cpp
inline TOML_PURE_INLINE_GETTER std::ostream & stream() const
```


### function indent

```cpp
inline TOML_PURE_INLINE_GETTER int indent() const
```


### function indent

```cpp
inline void indent(
    int level
)
```


### function increase_indent

```cpp
inline void increase_indent()
```


### function decrease_indent

```cpp
inline void decrease_indent()
```


### function indent_columns

```cpp
inline TOML_PURE_INLINE_GETTER size_t indent_columns() const
```


### function indent_array_elements

```cpp
inline TOML_PURE_INLINE_GETTER bool indent_array_elements() const
```


### function indent_sub_tables

```cpp
inline TOML_PURE_INLINE_GETTER bool indent_sub_tables() const
```


### function literal_strings_allowed

```cpp
inline TOML_PURE_INLINE_GETTER bool literal_strings_allowed() const
```


### function multi_line_strings_allowed

```cpp
inline TOML_PURE_INLINE_GETTER bool multi_line_strings_allowed() const
```


### function real_tabs_in_strings_allowed

```cpp
inline TOML_PURE_INLINE_GETTER bool real_tabs_in_strings_allowed() const
```


### function unicode_strings_allowed

```cpp
inline TOML_PURE_INLINE_GETTER bool unicode_strings_allowed() const
```


### function attach

```cpp
TOML_EXPORTED_MEMBER_FUNCTION void attach(
    std::ostream & stream
)
```


### function detach

```cpp
TOML_EXPORTED_MEMBER_FUNCTION void detach()
```


### function print_newline

```cpp
TOML_EXPORTED_MEMBER_FUNCTION void print_newline(
    bool force =false
)
```


### function print_indent

```cpp
TOML_EXPORTED_MEMBER_FUNCTION void print_indent()
```


### function print_unformatted

```cpp
TOML_EXPORTED_MEMBER_FUNCTION void print_unformatted(
    char c
)
```


### function print_unformatted

```cpp
TOML_EXPORTED_MEMBER_FUNCTION void print_unformatted(
    std::string_view str
)
```


### function print_string

```cpp
TOML_EXPORTED_MEMBER_FUNCTION void print_string(
    std::string_view str,
    bool allow_multi_line =true,
    bool allow_bare =false
)
```


### function print

```cpp
TOML_EXPORTED_MEMBER_FUNCTION void print(
    const value< std::string > & val
)
```


### function print

```cpp
TOML_EXPORTED_MEMBER_FUNCTION void print(
    const value< int64_t > & val
)
```


### function print

```cpp
TOML_EXPORTED_MEMBER_FUNCTION void print(
    const value< double > & val
)
```


### function print

```cpp
TOML_EXPORTED_MEMBER_FUNCTION void print(
    const value< bool > & val
)
```


### function print

```cpp
TOML_EXPORTED_MEMBER_FUNCTION void print(
    const value< date > & val
)
```


### function print

```cpp
TOML_EXPORTED_MEMBER_FUNCTION void print(
    const value< time > & val
)
```


### function print

```cpp
TOML_EXPORTED_MEMBER_FUNCTION void print(
    const value< date_time > & val
)
```


### function print_value

```cpp
TOML_EXPORTED_MEMBER_FUNCTION void print_value(
    const node & val_node,
    node_type type
)
```


### function dump_failed_parse_result

```cpp
TOML_NODISCARDTOML_EXPORTED_MEMBER_FUNCTION bool dump_failed_parse_result()
```


### function formatter

```cpp
TOML_NODISCARD_CTORTOML_EXPORTED_MEMBER_FUNCTION formatter(
    const node * source_node,
    const parse_result * source_pr,
    const formatter_constants & constants,
    const formatter_config & config
)
```



_Automatically updated on 2022-05-02 at 01:42:07 +0000._