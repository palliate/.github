---
title: TOML_PARSE_ERROR_BASE
summary: An error generated when parsing fails. 
parent: Classes
grand_parent: libpalliate
layout: default
---

# TOML_PARSE_ERROR_BASE



An error generated when parsing fails.  [More...](#detailed-description)


`#include <toml.hpp>`

## Public Functions

|                | Name           |
| -------------- | -------------- |
| [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor) | **[parse_error](/libpalliate/generated/Classes/classTOML__PARSE__ERROR__BASE#function-parse-error)**(std::string && desc, [source_region](/libpalliate/generated/Classes/structsource__region) && src) |
| [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor) | **[parse_error](/libpalliate/generated/Classes/classTOML__PARSE__ERROR__BASE#function-parse-error)**(std::string && desc, const [source_region](/libpalliate/generated/Classes/structsource__region) & src) |
| [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor) | **[parse_error](/libpalliate/generated/Classes/classTOML__PARSE__ERROR__BASE#function-parse-error)**(std::string && desc, const [source_position](/libpalliate/generated/Classes/structsource__position) & position, const [source_path_ptr](/libpalliate/generated/Files/source__region_8h#using-source-path-ptr) & path ={}) |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) std::string_view | **[description](/libpalliate/generated/Classes/classTOML__PARSE__ERROR__BASE#function-description)**() const<br>Returns a textual description of the error.  |
| const [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[source_region](/libpalliate/generated/Classes/structsource__region) & | **[source](/libpalliate/generated/Classes/classTOML__PARSE__ERROR__BASE#function-source)**() const<br>Returns the region of the source document responsible for the error.  |
| [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor) | **[parse_error](/libpalliate/generated/Classes/classTOML__PARSE__ERROR__BASE#function-parse-error)**(std::string && desc, [source_region](/libpalliate/generated/Classes/structsource__region) && src) |
| [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor) | **[parse_error](/libpalliate/generated/Classes/classTOML__PARSE__ERROR__BASE#function-parse-error)**(std::string && desc, const [source_region](/libpalliate/generated/Classes/structsource__region) & src) |
| [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor) | **[parse_error](/libpalliate/generated/Classes/classTOML__PARSE__ERROR__BASE#function-parse-error)**(std::string && desc, const [source_position](/libpalliate/generated/Classes/structsource__position) & position, const [source_path_ptr](/libpalliate/generated/Files/source__region_8h#using-source-path-ptr) & path ={}) |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) std::string_view | **[description](/libpalliate/generated/Classes/classTOML__PARSE__ERROR__BASE#function-description)**() const |
| const [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[source_region](/libpalliate/generated/Classes/structsource__region) & | **[source](/libpalliate/generated/Classes/classTOML__PARSE__ERROR__BASE#function-source)**() const |

## Friends

|                | Name           |
| -------------- | -------------- |
| std::ostream & | **[operator<<](/libpalliate/generated/Classes/classTOML__PARSE__ERROR__BASE#friend-operator<<)**(std::ostream & lhs, const [parse_error](/libpalliate/generated/Classes/classTOML__PARSE__ERROR__BASE#function-parse-error) & rhs) <br>Prints a parse_error to a stream.  |
| std::ostream & | **[operator<<](/libpalliate/generated/Classes/classTOML__PARSE__ERROR__BASE#friend-operator<<)**(std::ostream & lhs, const [parse_error](/libpalliate/generated/Classes/classTOML__PARSE__ERROR__BASE#function-parse-error) & rhs)  |

## Detailed Description

```cpp
class TOML_PARSE_ERROR_BASE;
```

An error generated when parsing fails. 

**Remark**: This class inherits from std::runtime_error when exceptions are enabled. The public interface is the same regardless of exception mode. 
## Public Functions Documentation

### function parse_error

```cpp
inline TOML_NODISCARD_CTOR parse_error(
    std::string && desc,
    source_region && src
)
```


### function parse_error

```cpp
inline TOML_NODISCARD_CTOR parse_error(
    std::string && desc,
    const source_region & src
)
```


### function parse_error

```cpp
inline TOML_NODISCARD_CTOR parse_error(
    std::string && desc,
    const source_position & position,
    const source_path_ptr & path ={}
)
```


### function description

```cpp
inline TOML_NODISCARD std::string_view description() const
```

Returns a textual description of the error. 

**Remark**: The backing string is guaranteed to be null-terminated. 

### function source

```cpp
inline const TOML_NODISCARDsource_region & source() const
```

Returns the region of the source document responsible for the error. 

### function parse_error

```cpp
inline TOML_NODISCARD_CTOR parse_error(
    std::string && desc,
    source_region && src
)
```


### function parse_error

```cpp
inline TOML_NODISCARD_CTOR parse_error(
    std::string && desc,
    const source_region & src
)
```


### function parse_error

```cpp
inline TOML_NODISCARD_CTOR parse_error(
    std::string && desc,
    const source_position & position,
    const source_path_ptr & path ={}
)
```


### function description

```cpp
inline TOML_NODISCARD std::string_view description() const
```


**Remark**: The backing string is guaranteed to be null-terminated. 

### function source

```cpp
inline const TOML_NODISCARDsource_region & source() const
```


## Friends

### friend operator<<

```cpp
friend std::ostream & operator<<(
    std::ostream & lhs,

    const parse_error & rhs
);
```

Prints a parse_error to a stream. 

**Parameters**: 

  * **lhs** The stream. 
  * **rhs** The parse_error.


**Template Parameters**: 

  * **Char** The output stream's underlying character type. Must be 1 byte in size. 


**Return**: The input stream. 

\detail \cpp try { auto tbl = toml::parse("enabled = trUe"sv); } catch (const toml::parse_error & err) { std::cerr << "Parsing failed:\n"sv << err << "\n"; } \ecpp

\out Parsing failed: Encountered unexpected character while parsing boolean; expected 'true', saw 'trU' (error occurred at line 1, column 13) \eout


### friend operator<<

```cpp
friend std::ostream & operator<<(
    std::ostream & lhs,

    const parse_error & rhs
);
```


**Parameters**: 

  * **lhs** The stream. 
  * **rhs** The parse_error.


**Template Parameters**: 

  * **Char** The output stream's underlying character type. Must be 1 byte in size. 


**Return**: The input stream. 

\detail \cpp try { auto tbl = toml::parse("enabled = trUe"sv); } catch (const toml::parse_error & err) { std::cerr << "Parsing failed:\n"sv << err << "\n"; } \ecpp

\out Parsing failed: Encountered unexpected character while parsing boolean; expected 'true', saw 'trU' (error occurred at line 1, column 13) \eout



_Automatically updated on 2022-05-02 at 01:42:07 +0000._