---
title: source_region
summary: A source document region. 
parent: Classes
grand_parent: libpalliate
layout: default
---

# source_region



A source document region.  [More...](#detailed-description)


`#include <toml.hpp>`

## Public Functions

|                | Name           |
| -------------- | -------------- |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) optional< std::wstring > | **[wide_path](/libpalliate/generated/Classes/structsource__region#function-wide-path)**() const<br>The path to the corresponding source document as a wide-string.  |

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| [source_position](/libpalliate/generated/Classes/structsource__position) | **[begin](/libpalliate/generated/Classes/structsource__region#variable-begin)** <br>The beginning of the region (inclusive).  |
| [source_position](/libpalliate/generated/Classes/structsource__position) | **[end](/libpalliate/generated/Classes/structsource__region#variable-end)** <br>The end of the region (exclusive).  |
| [source_path_ptr](/libpalliate/generated/Files/source__region_8h#using-source-path-ptr) | **[path](/libpalliate/generated/Classes/structsource__region#variable-path)** <br>The path to the corresponding source document.  |

## Friends

|                | Name           |
| -------------- | -------------- |
| std::ostream & | **[operator<<](/libpalliate/generated/Classes/structsource__region#friend-operator<<)**(std::ostream & lhs, const [source_region](/libpalliate/generated/Classes/structsource__region) & rhs) <br>Prints a [source_region](/libpalliate/generated/Classes/structsource__region) to a stream.  |
| std::ostream & | **[operator<<](/libpalliate/generated/Classes/structsource__region#friend-operator<<)**(std::ostream & lhs, const [source_region](/libpalliate/generated/Classes/structsource__region) & rhs)  |

## Detailed Description

```cpp
struct source_region;
```

A source document region. 

**Remark**: toml++'s parser is unicode-aware insofar as it knows how to handle non-ASCII whitespace and newline characters, but it doesn't give much thought to combining marks, grapheme clusters vs. characters, et cetera. If a TOML document contains lots of codepoints outside of the ASCII range you may find that your source_positions don't match those given by a text editor (typically the line numbers will be accurate but column numbers will be too high). **This is not an error.** I've chosen this behaviour as a deliberate trade-off between parser complexity and correctness. 

\detail \cpp auto tbl = toml::parse_file("config.toml"sv); if (auto server = tbl.get("server")) { std::cout << "begin: "sv << server->source().begin << "\n"; std::cout << "end: "sv << server->source().end << "\n"; std::cout << "path: "sv << *server->source().path << "\n"; } \ecpp

\out begin: line 3, column 1 end: line 3, column 22 path: config.toml \eout

## Public Functions Documentation

### function wide_path

```cpp
inline TOML_NODISCARD optional< std::wstring > wide_path() const
```

The path to the corresponding source document as a wide-string. 

**Remark**: This will return an empty optional if no path was provided to toml::parse(). 

\availability This function is only available when [TOML_ENABLE_WINDOWS_COMPAT](/libpalliate/generated/Files/toml_8hpp#define-toml-enable-windows-compat) is enabled.


## Public Attributes Documentation

### variable begin

```cpp
source_position begin;
```

The beginning of the region (inclusive). 

### variable end

```cpp
source_position end;
```

The end of the region (exclusive). 

### variable path

```cpp
source_path_ptr path;
```

The path to the corresponding source document. 

**Remark**: This will be `nullptr` if no path was provided to toml::parse(). 

## Friends

### friend operator<<

```cpp
friend std::ostream & operator<<(
    std::ostream & lhs,

    const source_region & rhs
);
```

Prints a [source_region](/libpalliate/generated/Classes/structsource__region) to a stream. 

**Parameters**: 

  * **lhs** The stream. 
  * **rhs** The [source_position](/libpalliate/generated/Classes/structsource__position).


**Return**: The input stream. 

\detail \cpp auto tbl = toml::parse("bar = 42", "config.toml");

std::cout << "The value for 'bar' was found on "sv << tbl.get("bar")->source() << "\n"; \ecpp

\out The value for 'bar' was found on line 1, column 7 of 'config.toml' \eout


### friend operator<<

```cpp
friend std::ostream & operator<<(
    std::ostream & lhs,

    const source_region & rhs
);
```


**Parameters**: 

  * **lhs** The stream. 
  * **rhs** The [source_position](/libpalliate/generated/Classes/structsource__position).


**Return**: The input stream. 

\detail \cpp auto tbl = toml::parse("bar = 42", "config.toml");

std::cout << "The value for 'bar' was found on "sv << tbl.get("bar")->source() << "\n"; \ecpp

\out The value for 'bar' was found on line 1, column 7 of 'config.toml' \eout



_Automatically updated on 2022-05-02 at 01:42:07 +0000._