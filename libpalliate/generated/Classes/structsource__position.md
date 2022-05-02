---
title: source_position
summary: A source document line-and-column pair. 
parent: Classes
grand_parent: libpalliate
layout: default
---

# source_position



A source document line-and-column pair.  [More...](#detailed-description)


`#include <toml.hpp>`

## Public Functions

|                | Name           |
| -------------- | -------------- |
| constexpr [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) | **[operator bool](/libpalliate/generated/Classes/structsource__position#function-operator-bool)**() const<br>Returns true if both line and column numbers are non-zero.  |
| constexpr [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) | **[operator bool](/libpalliate/generated/Classes/structsource__position#function-operator-bool)**() const |

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| source_index | **[line](/libpalliate/generated/Classes/structsource__position#variable-line)** <br>The line number.  |
| source_index | **[column](/libpalliate/generated/Classes/structsource__position#variable-column)** <br>The column number.  |

## Friends

|                | Name           |
| -------------- | -------------- |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) constexpr friend bool | **[operator==](/libpalliate/generated/Classes/structsource__position#friend-operator==)**(const [source_position](/libpalliate/generated/Classes/structsource__position) & lhs, const [source_position](/libpalliate/generated/Classes/structsource__position) & rhs) <br>Returns true if two source_positions represent the same line and column.  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) constexpr friend bool | **[operator!=](/libpalliate/generated/Classes/structsource__position#friend-operator!=)**(const [source_position](/libpalliate/generated/Classes/structsource__position) & lhs, const [source_position](/libpalliate/generated/Classes/structsource__position) & rhs) <br>Returns true if two source_positions do not represent the same line and column.  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) constexpr friend bool | **[operator<](/libpalliate/generated/Classes/structsource__position#friend-operator<)**(const [source_position](/libpalliate/generated/Classes/structsource__position) & lhs, const [source_position](/libpalliate/generated/Classes/structsource__position) & rhs) <br>Returns true if the LHS position is before the RHS position.  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) constexpr friend bool | **[operator<=](/libpalliate/generated/Classes/structsource__position#friend-operator<=)**(const [source_position](/libpalliate/generated/Classes/structsource__position) & lhs, const [source_position](/libpalliate/generated/Classes/structsource__position) & rhs) <br>Returns true if the LHS position is before the RHS position or equal to it.  |
| std::ostream & | **[operator<<](/libpalliate/generated/Classes/structsource__position#friend-operator<<)**(std::ostream & lhs, const [source_position](/libpalliate/generated/Classes/structsource__position) & rhs) <br>Prints a [source_position](/libpalliate/generated/Classes/structsource__position) to a stream.  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) constexpr friend bool | **[operator==](/libpalliate/generated/Classes/structsource__position#friend-operator==)**(const [source_position](/libpalliate/generated/Classes/structsource__position) & lhs, const [source_position](/libpalliate/generated/Classes/structsource__position) & rhs)  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) constexpr friend bool | **[operator!=](/libpalliate/generated/Classes/structsource__position#friend-operator!=)**(const [source_position](/libpalliate/generated/Classes/structsource__position) & lhs, const [source_position](/libpalliate/generated/Classes/structsource__position) & rhs)  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) constexpr friend bool | **[operator<](/libpalliate/generated/Classes/structsource__position#friend-operator<)**(const [source_position](/libpalliate/generated/Classes/structsource__position) & lhs, const [source_position](/libpalliate/generated/Classes/structsource__position) & rhs)  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) constexpr friend bool | **[operator<=](/libpalliate/generated/Classes/structsource__position#friend-operator<=)**(const [source_position](/libpalliate/generated/Classes/structsource__position) & lhs, const [source_position](/libpalliate/generated/Classes/structsource__position) & rhs)  |
| std::ostream & | **[operator<<](/libpalliate/generated/Classes/structsource__position#friend-operator<<)**(std::ostream & lhs, const [source_position](/libpalliate/generated/Classes/structsource__position) & rhs)  |

## Detailed Description

```cpp
struct source_position;
```

A source document line-and-column pair. 

**Remark**: toml++'s parser is unicode-aware insofar as it knows how to handle non-ASCII whitespace and newline characters, but it doesn't give much thought to combining marks, grapheme clusters vs. characters, et cetera. If a TOML document contains lots of codepoints outside of the ASCII range you may find that your source_positions don't match those given by a text editor (typically the line numbers will be accurate but column numbers will be too high). **This is not an error.** I've chosen this behaviour as a deliberate trade-off between parser complexity and correctness. 

\detail \cpp auto table = toml::parse_file("config.toml"sv); std::cout << "The node 'description' was defined at "sv << [table.get](/libpalliate/generated/Classes/classtable#function-get)("description")->source().begin() << "\n"; \ecpp

\out The value 'description' was defined at line 7, column 15 \eout

## Public Functions Documentation

### function operator bool

```cpp
inline explicit constexpr TOML_NODISCARD operator bool() const
```

Returns true if both line and column numbers are non-zero. 

### function operator bool

```cpp
inline explicit constexpr TOML_NODISCARD operator bool() const
```


## Public Attributes Documentation

### variable line

```cpp
source_index line;
```

The line number. 

**Remark**: Valid line numbers start at 1. 

### variable column

```cpp
source_index column;
```

The column number. 

**Remark**: Valid column numbers start at 1. 

## Friends

### friend operator==

```cpp
friend TOML_NODISCARD constexpr friend bool operator==(
    const source_position & lhs,

    const source_position & rhs
);
```

Returns true if two source_positions represent the same line and column. 

### friend operator!=

```cpp
friend TOML_NODISCARD constexpr friend bool operator!=(
    const source_position & lhs,

    const source_position & rhs
);
```

Returns true if two source_positions do not represent the same line and column. 

### friend operator<

```cpp
friend TOML_NODISCARD constexpr friend bool operator<(
    const source_position & lhs,

    const source_position & rhs
);
```

Returns true if the LHS position is before the RHS position. 

### friend operator<=

```cpp
friend TOML_NODISCARD constexpr friend bool operator<=(
    const source_position & lhs,

    const source_position & rhs
);
```

Returns true if the LHS position is before the RHS position or equal to it. 

### friend operator<<

```cpp
friend std::ostream & operator<<(
    std::ostream & lhs,

    const source_position & rhs
);
```

Prints a [source_position](/libpalliate/generated/Classes/structsource__position) to a stream. 

**Parameters**: 

  * **lhs** The stream. 
  * **rhs** The [source_position](/libpalliate/generated/Classes/structsource__position).


**Return**: The input stream. 

\detail \cpp auto tbl = toml::parse("bar = 42"sv);

std::cout << "The value for 'bar' was found on "sv << tbl.get("bar")->source().begin() << "\n"; \ecpp

\out The value for 'bar' was found on line 1, column 7 \eout


### friend operator==

```cpp
friend TOML_NODISCARD constexpr friend bool operator==(
    const source_position & lhs,

    const source_position & rhs
);
```


### friend operator!=

```cpp
friend TOML_NODISCARD constexpr friend bool operator!=(
    const source_position & lhs,

    const source_position & rhs
);
```


### friend operator<

```cpp
friend TOML_NODISCARD constexpr friend bool operator<(
    const source_position & lhs,

    const source_position & rhs
);
```


### friend operator<=

```cpp
friend TOML_NODISCARD constexpr friend bool operator<=(
    const source_position & lhs,

    const source_position & rhs
);
```


### friend operator<<

```cpp
friend std::ostream & operator<<(
    std::ostream & lhs,

    const source_position & rhs
);
```


**Parameters**: 

  * **lhs** The stream. 
  * **rhs** The [source_position](/libpalliate/generated/Classes/structsource__position).


**Return**: The input stream. 

\detail \cpp auto tbl = toml::parse("bar = 42"sv);

std::cout << "The value for 'bar' was found on "sv << tbl.get("bar")->source().begin() << "\n"; \ecpp

\out The value for 'bar' was found on line 1, column 7 \eout



_Automatically updated on 2022-05-02 at 01:42:07 +0000._