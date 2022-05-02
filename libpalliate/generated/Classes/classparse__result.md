---
title: parse_result
summary: The result of a parsing operation. 
parent: Classes
grand_parent: libpalliate
layout: default
---

# parse_result



The result of a parsing operation.  [More...](#detailed-description)


`#include <toml.hpp>`

## Public Types

|                | Name           |
| -------------- | -------------- |
| using [table_iterator](/libpalliate/generated/Classes/classtable__iterator) | **[iterator](/libpalliate/generated/Classes/classparse__result#using-iterator)** <br>A BidirectionalIterator for iterating over key-value pairs in a wrapped toml::table.  |
| using [const_table_iterator](/libpalliate/generated/Files/table_8h#using-const-table-iterator) | **[const_iterator](/libpalliate/generated/Classes/classparse__result#using-const-iterator)** <br>A BidirectionalIterator for iterating over const key-value pairs in a wrapped toml::table.  |
| using [table_iterator](/libpalliate/generated/Classes/classtable__iterator) | **[iterator](/libpalliate/generated/Classes/classparse__result#using-iterator)**  |
| using [const_table_iterator](/libpalliate/generated/Files/table_8h#using-const-table-iterator) | **[const_iterator](/libpalliate/generated/Classes/classparse__result#using-const-iterator)**  |

## Public Functions

|                | Name           |
| -------------- | -------------- |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) bool | **[succeeded](/libpalliate/generated/Classes/classparse__result#function-succeeded)**() const<br>Returns true if parsing succeeeded.  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) bool | **[failed](/libpalliate/generated/Classes/classparse__result#function-failed)**() const<br>Returns true if parsing failed.  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) | **[operator bool](/libpalliate/generated/Classes/classparse__result#function-operator-bool)**() const<br>Returns true if parsing succeeded.  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) toml::table & | **[table](/libpalliate/generated/Classes/classparse__result#function-table)**()<br>Returns the internal toml::table.  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) toml::table && | **[table](/libpalliate/generated/Classes/classparse__result#function-table)**()<br>Returns the internal toml::table (rvalue overload).  |
| const [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) toml::table & | **[table](/libpalliate/generated/Classes/classparse__result#function-table)**() const<br>Returns the internal toml::table (const lvalue overload).  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) | **[operator toml::table &](/libpalliate/generated/Classes/classparse__result#function-operator-tomltable-&)**()<br>Returns the internal toml::table.  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) | **[operator toml::table &&](/libpalliate/generated/Classes/classparse__result#function-operator-tomltable-&&)**()<br>Returns the internal toml::table (rvalue overload).  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) | **[operator const toml::table &](/libpalliate/generated/Classes/classparse__result#function-operator-const-tomltable-&)**() const<br>Returns the internal toml::table (const lvalue overload).  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) parse_error & | **[error](/libpalliate/generated/Classes/classparse__result#function-error)**()<br>Returns the internal toml::parse_error.  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) parse_error && | **[error](/libpalliate/generated/Classes/classparse__result#function-error)**()<br>Returns the internal toml::parse_error (rvalue overload).  |
| const [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) parse_error & | **[error](/libpalliate/generated/Classes/classparse__result#function-error)**() const<br>Returns the internal toml::parse_error (const lvalue overload).  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) | **[operator parse_error &](/libpalliate/generated/Classes/classparse__result#function-operator-parse-error-&)**()<br>Returns the internal toml::parse_error.  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) | **[operator parse_error &&](/libpalliate/generated/Classes/classparse__result#function-operator-parse-error-&&)**()<br>Returns the internal toml::parse_error (rvalue overload).  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) | **[operator const parse_error &](/libpalliate/generated/Classes/classparse__result#function-operator-const-parse-error-&)**() const<br>Returns the internal toml::parse_error (const lvalue overload).  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[table_iterator](/libpalliate/generated/Classes/classtable__iterator) | **[begin](/libpalliate/generated/Classes/classparse__result#function-begin)**()<br>Returns an iterator to the first key-value pair in the wrapped table.  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[const_table_iterator](/libpalliate/generated/Files/table_8h#using-const-table-iterator) | **[begin](/libpalliate/generated/Classes/classparse__result#function-begin)**() const<br>Returns an iterator to the first key-value pair in the wrapped table.  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[const_table_iterator](/libpalliate/generated/Files/table_8h#using-const-table-iterator) | **[cbegin](/libpalliate/generated/Classes/classparse__result#function-cbegin)**() const<br>Returns an iterator to the first key-value pair in the wrapped table.  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[table_iterator](/libpalliate/generated/Classes/classtable__iterator) | **[end](/libpalliate/generated/Classes/classparse__result#function-end)**()<br>Returns an iterator to one-past-the-last key-value pair in the wrapped table.  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[const_table_iterator](/libpalliate/generated/Files/table_8h#using-const-table-iterator) | **[end](/libpalliate/generated/Classes/classparse__result#function-end)**() const<br>Returns an iterator to one-past-the-last key-value pair in the wrapped table.  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[const_table_iterator](/libpalliate/generated/Files/table_8h#using-const-table-iterator) | **[cend](/libpalliate/generated/Classes/classparse__result#function-cend)**() const<br>Returns an iterator to one-past-the-last key-value pair in the wrapped table.  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[node_view](/libpalliate/generated/Classes/classnode__view)< node > | **[operator[]](/libpalliate/generated/Classes/classparse__result#function-operator[])**(std::string_view key)<br>Gets a [node_view]() for the selected key-value pair in the wrapped table.  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[node_view](/libpalliate/generated/Classes/classnode__view)< const node > | **[operator[]](/libpalliate/generated/Classes/classparse__result#function-operator[])**(std::string_view key) const<br>Gets a [node_view]() for the selected key-value pair in the wrapped table (const overload).  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[node_view](/libpalliate/generated/Classes/classnode__view)< node > | **[at_path](/libpalliate/generated/Classes/classparse__result#function-at-path)**(std::string_view path)<br>Returns a view of the subnode matching a fully-qualified "TOML path".  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[node_view](/libpalliate/generated/Classes/classnode__view)< const node > | **[at_path](/libpalliate/generated/Classes/classparse__result#function-at-path)**(std::string_view path) const<br>Returns a const view of the subnode matching a fully-qualified "TOML path".  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[node_view](/libpalliate/generated/Classes/classnode__view)< node > | **[operator[]](/libpalliate/generated/Classes/classparse__result#function-operator[])**(std::wstring_view key)<br>Gets a [node_view]() for the selected key-value pair in the wrapped table.  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[node_view](/libpalliate/generated/Classes/classnode__view)< const node > | **[operator[]](/libpalliate/generated/Classes/classparse__result#function-operator[])**(std::wstring_view key) const<br>Gets a [node_view]() for the selected key-value pair in the wrapped table (const overload).  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[node_view](/libpalliate/generated/Classes/classnode__view)< node > | **[at_path](/libpalliate/generated/Classes/classparse__result#function-at-path)**(std::wstring_view path)<br>Returns a view of the subnode matching a fully-qualified "TOML path".  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[node_view](/libpalliate/generated/Classes/classnode__view)< const node > | **[at_path](/libpalliate/generated/Classes/classparse__result#function-at-path)**(std::wstring_view path) const<br>Returns a const view of the subnode matching a fully-qualified "TOML path".  |
| [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor) | **[parse_result](/libpalliate/generated/Classes/classparse__result#function-parse-result)**()<br>Default constructs an 'error' result.  |
| [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor) | **[parse_result](/libpalliate/generated/Classes/classparse__result#function-parse-result)**(toml::table && tbl) |
| [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor) | **[parse_result](/libpalliate/generated/Classes/classparse__result#function-parse-result)**(parse_error && err) |
| [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor) | **[parse_result](/libpalliate/generated/Classes/classparse__result#function-parse-result)**([parse_result](/libpalliate/generated/Classes/classparse__result) && res)<br>Move constructor.  |
| [parse_result](/libpalliate/generated/Classes/classparse__result) & | **[operator=](/libpalliate/generated/Classes/classparse__result#function-operator=)**([parse_result](/libpalliate/generated/Classes/classparse__result) && rhs)<br>Move-assignment operator.  |
| | **[~parse_result](/libpalliate/generated/Classes/classparse__result#function-~parse-result)**()<br>Destructor.  |
| [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor) | **[parse_result](/libpalliate/generated/Classes/classparse__result#function-parse-result)**() |
| [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor) | **[parse_result](/libpalliate/generated/Classes/classparse__result#function-parse-result)**(toml::table && tbl) |
| [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor) | **[parse_result](/libpalliate/generated/Classes/classparse__result#function-parse-result)**(parse_error && err) |
| [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor) | **[parse_result](/libpalliate/generated/Classes/classparse__result#function-parse-result)**([parse_result](/libpalliate/generated/Classes/classparse__result) && res) |
| [parse_result](/libpalliate/generated/Classes/classparse__result) & | **[operator=](/libpalliate/generated/Classes/classparse__result#function-operator=)**([parse_result](/libpalliate/generated/Classes/classparse__result) && rhs) |
| | **[~parse_result](/libpalliate/generated/Classes/classparse__result#function-~parse-result)**() |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) bool | **[succeeded](/libpalliate/generated/Classes/classparse__result#function-succeeded)**() const |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) bool | **[failed](/libpalliate/generated/Classes/classparse__result#function-failed)**() const |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) | **[operator bool](/libpalliate/generated/Classes/classparse__result#function-operator-bool)**() const |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) toml::table & | **[table](/libpalliate/generated/Classes/classparse__result#function-table)**() |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) toml::table && | **[table](/libpalliate/generated/Classes/classparse__result#function-table)**() |
| const [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) toml::table & | **[table](/libpalliate/generated/Classes/classparse__result#function-table)**() const |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) | **[operator toml::table &](/libpalliate/generated/Classes/classparse__result#function-operator-tomltable-&)**() |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) | **[operator toml::table &&](/libpalliate/generated/Classes/classparse__result#function-operator-tomltable-&&)**() |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) | **[operator const toml::table &](/libpalliate/generated/Classes/classparse__result#function-operator-const-tomltable-&)**() const |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) parse_error & | **[error](/libpalliate/generated/Classes/classparse__result#function-error)**() |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) parse_error && | **[error](/libpalliate/generated/Classes/classparse__result#function-error)**() |
| const [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) parse_error & | **[error](/libpalliate/generated/Classes/classparse__result#function-error)**() const |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) | **[operator parse_error &](/libpalliate/generated/Classes/classparse__result#function-operator-parse-error-&)**() |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) | **[operator parse_error &&](/libpalliate/generated/Classes/classparse__result#function-operator-parse-error-&&)**() |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) | **[operator const parse_error &](/libpalliate/generated/Classes/classparse__result#function-operator-const-parse-error-&)**() const |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[table_iterator](/libpalliate/generated/Classes/classtable__iterator) | **[begin](/libpalliate/generated/Classes/classparse__result#function-begin)**() |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[const_table_iterator](/libpalliate/generated/Files/table_8h#using-const-table-iterator) | **[begin](/libpalliate/generated/Classes/classparse__result#function-begin)**() const |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[const_table_iterator](/libpalliate/generated/Files/table_8h#using-const-table-iterator) | **[cbegin](/libpalliate/generated/Classes/classparse__result#function-cbegin)**() const |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[table_iterator](/libpalliate/generated/Classes/classtable__iterator) | **[end](/libpalliate/generated/Classes/classparse__result#function-end)**() |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[const_table_iterator](/libpalliate/generated/Files/table_8h#using-const-table-iterator) | **[end](/libpalliate/generated/Classes/classparse__result#function-end)**() const |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[const_table_iterator](/libpalliate/generated/Files/table_8h#using-const-table-iterator) | **[cend](/libpalliate/generated/Classes/classparse__result#function-cend)**() const |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[node_view](/libpalliate/generated/Classes/classnode__view)< node > | **[operator[]](/libpalliate/generated/Classes/classparse__result#function-operator[])**(std::string_view key) |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[node_view](/libpalliate/generated/Classes/classnode__view)< const node > | **[operator[]](/libpalliate/generated/Classes/classparse__result#function-operator[])**(std::string_view key) const |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[node_view](/libpalliate/generated/Classes/classnode__view)< node > | **[at_path](/libpalliate/generated/Classes/classparse__result#function-at-path)**(std::string_view path) |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[node_view](/libpalliate/generated/Classes/classnode__view)< const node > | **[at_path](/libpalliate/generated/Classes/classparse__result#function-at-path)**(std::string_view path) const |

## Friends

|                | Name           |
| -------------- | -------------- |
| std::ostream & | **[operator<<](/libpalliate/generated/Classes/classparse__result#friend-operator<<)**(std::ostream & os, const [parse_result](/libpalliate/generated/Classes/classparse__result) & result) <br>Prints the held error or table object out to a text stream.  |
| std::ostream & | **[operator<<](/libpalliate/generated/Classes/classparse__result#friend-operator<<)**(std::ostream & os, const [parse_result](/libpalliate/generated/Classes/classparse__result) & result)  |

## Detailed Description

```cpp
class parse_result;
```

The result of a parsing operation. 

\availability **This type only exists when exceptions are disabled.** Otherwise [parse_result](/libpalliate/generated/Classes/classparse__result) is just an alias for toml::table: \cpp #if TOML_EXCEPTIONS using [parse_result](/libpalliate/generated/Classes/classparse__result) = table; #else class [parse_result](/libpalliate/generated/Classes/classparse__result) { // ... #endif \ecpp

\detail A [parse_result](/libpalliate/generated/Classes/classparse__result) is effectively a discriminated union containing either a toml::table or a toml::parse_error. Most member functions assume a particular one of these two states, and calling them when in the wrong state will cause errors (e.g. attempting to access the error object when parsing was successful). \cpp toml::parse_result result = toml::parse_file("config.toml"); if (result) do_stuff_with_a_table(result); //implicitly converts to table& else std::cerr << "Parse failed:\n"sv << [result.error()](/libpalliate/generated/Namespaces/namespacelogging#enumvalue-error) << "\n"; \ecpp

\out example output:

Parse failed: Encountered unexpected character while parsing boolean; expected 'true', saw 'trU' (error occurred at line 1, column 13 of 'config.toml') \eout

Getting node_views (`operator[]`, `[at_path()](/libpalliate/generated/Classes/classparse__result#function-at-path)`) and using the iterator accessor functions (`[begin()](/libpalliate/generated/Classes/classparse__result#function-begin)`, `[end()](/libpalliate/generated/Classes/classparse__result#function-end)` etc.) are unconditionally safe; when parsing fails these just return 'empty' values. A ranged-for loop on a failed [parse_result](/libpalliate/generated/Classes/classparse__result) is also safe since `[begin()](/libpalliate/generated/Classes/classparse__result#function-begin)` and `[end()](/libpalliate/generated/Classes/classparse__result#function-end)` return the same iterator and will not lead to any dereferences and iterations. 

## Public Types Documentation

### using iterator

```cpp
using parse_result::iterator =  table_iterator;
```

A BidirectionalIterator for iterating over key-value pairs in a wrapped toml::table. 

### using const_iterator

```cpp
using parse_result::const_iterator =  const_table_iterator;
```

A BidirectionalIterator for iterating over const key-value pairs in a wrapped toml::table. 

### using iterator

```cpp
using parse_result::iterator =  table_iterator;
```


### using const_iterator

```cpp
using parse_result::const_iterator =  const_table_iterator;
```


## Public Functions Documentation

### function succeeded

```cpp
inline TOML_NODISCARD bool succeeded() const
```

Returns true if parsing succeeeded. 

### function failed

```cpp
inline TOML_NODISCARD bool failed() const
```

Returns true if parsing failed. 

### function operator bool

```cpp
inline explicit TOML_NODISCARD operator bool() const
```

Returns true if parsing succeeded. 

### function table

```cpp
inline TOML_NODISCARD toml::table & table()
```

Returns the internal toml::table. 

### function table

```cpp
inline TOML_NODISCARD toml::table && table()
```

Returns the internal toml::table (rvalue overload). 

### function table

```cpp
inline const TOML_NODISCARD toml::table & table() const
```

Returns the internal toml::table (const lvalue overload). 

### function operator toml::table &

```cpp
inline TOML_NODISCARD operator toml::table &()
```

Returns the internal toml::table. 

### function operator toml::table &&

```cpp
inline TOML_NODISCARD operator toml::table &&()
```

Returns the internal toml::table (rvalue overload). 

### function operator const toml::table &

```cpp
inline TOML_NODISCARD operator const toml::table &() const
```

Returns the internal toml::table (const lvalue overload). 

### function error

```cpp
inline TOML_NODISCARD parse_error & error()
```

Returns the internal toml::parse_error. 

### function error

```cpp
inline TOML_NODISCARD parse_error && error()
```

Returns the internal toml::parse_error (rvalue overload). 

### function error

```cpp
inline const TOML_NODISCARD parse_error & error() const
```

Returns the internal toml::parse_error (const lvalue overload). 

### function operator parse_error &

```cpp
inline explicit TOML_NODISCARD operator parse_error &()
```

Returns the internal toml::parse_error. 

### function operator parse_error &&

```cpp
inline explicit TOML_NODISCARD operator parse_error &&()
```

Returns the internal toml::parse_error (rvalue overload). 

### function operator const parse_error &

```cpp
inline explicit TOML_NODISCARD operator const parse_error &() const
```

Returns the internal toml::parse_error (const lvalue overload). 

### function begin

```cpp
inline TOML_NODISCARDtable_iterator begin()
```

Returns an iterator to the first key-value pair in the wrapped table. 

**Remark**: Always returns the same value as [end()](/libpalliate/generated/Classes/classparse__result#function-end) if parsing failed. 

### function begin

```cpp
inline TOML_NODISCARDconst_table_iterator begin() const
```

Returns an iterator to the first key-value pair in the wrapped table. 

**Remark**: Always returns the same value as [end()](/libpalliate/generated/Classes/classparse__result#function-end) if parsing failed. 

### function cbegin

```cpp
inline TOML_NODISCARDconst_table_iterator cbegin() const
```

Returns an iterator to the first key-value pair in the wrapped table. 

**Remark**: Always returns the same value as [cend()](/libpalliate/generated/Classes/classparse__result#function-cend) if parsing failed. 

### function end

```cpp
inline TOML_NODISCARDtable_iterator end()
```

Returns an iterator to one-past-the-last key-value pair in the wrapped table. 

### function end

```cpp
inline TOML_NODISCARDconst_table_iterator end() const
```

Returns an iterator to one-past-the-last key-value pair in the wrapped table. 

### function cend

```cpp
inline TOML_NODISCARDconst_table_iterator cend() const
```

Returns an iterator to one-past-the-last key-value pair in the wrapped table. 

### function operator[]

```cpp
inline TOML_NODISCARDnode_view< node > operator[](
    std::string_view key
)
```

Gets a [node_view]() for the selected key-value pair in the wrapped table. 

**Parameters**: 

  * **key** The key used for the lookup.


**See**: toml::node_view 

**Return**: A view of the value at the given key if parsing was successful and a matching key existed, or an empty node view.

### function operator[]

```cpp
inline TOML_NODISCARDnode_view< const node > operator[](
    std::string_view key
) const
```

Gets a [node_view]() for the selected key-value pair in the wrapped table (const overload). 

**Parameters**: 

  * **key** The key used for the lookup.


**See**: toml::node_view 

**Return**: A view of the value at the given key if parsing was successful and a matching key existed, or an empty node view.

### function at_path

```cpp
inline TOML_NODISCARDnode_view< node > at_path(
    std::string_view path
)
```

Returns a view of the subnode matching a fully-qualified "TOML path". 

**See**: #toml::node::at_path(std::string_view) 

### function at_path

```cpp
inline TOML_NODISCARDnode_view< const node > at_path(
    std::string_view path
) const
```

Returns a const view of the subnode matching a fully-qualified "TOML path". 

**See**: #toml::node::at_path(std::string_view) 

### function operator[]

```cpp
inline TOML_NODISCARDnode_view< node > operator[](
    std::wstring_view key
)
```

Gets a [node_view]() for the selected key-value pair in the wrapped table. 

**Parameters**: 

  * **key** The key used for the lookup.


**See**: toml::node_view 

**Return**: A view of the value at the given key if parsing was successful and a matching key existed, or an empty node view.

\availability This overload is only available when [TOML_ENABLE_WINDOWS_COMPAT](/libpalliate/generated/Files/toml_8hpp#define-toml-enable-windows-compat) is enabled.


### function operator[]

```cpp
inline TOML_NODISCARDnode_view< const node > operator[](
    std::wstring_view key
) const
```

Gets a [node_view]() for the selected key-value pair in the wrapped table (const overload). 

**Parameters**: 

  * **key** The key used for the lookup.


**See**: toml::node_view 

**Return**: A view of the value at the given key if parsing was successful and a matching key existed, or an empty node view.

\availability This overload is only available when [TOML_ENABLE_WINDOWS_COMPAT](/libpalliate/generated/Files/toml_8hpp#define-toml-enable-windows-compat) is enabled.


### function at_path

```cpp
inline TOML_NODISCARDnode_view< node > at_path(
    std::wstring_view path
)
```

Returns a view of the subnode matching a fully-qualified "TOML path". 

**See**: #toml::node::at_path(std::string_view) 

\availability This overload is only available when [TOML_ENABLE_WINDOWS_COMPAT](/libpalliate/generated/Files/toml_8hpp#define-toml-enable-windows-compat) is enabled.


### function at_path

```cpp
inline TOML_NODISCARDnode_view< const node > at_path(
    std::wstring_view path
) const
```

Returns a const view of the subnode matching a fully-qualified "TOML path". 

**See**: #toml::node::at_path(std::string_view) 

\availability This overload is only available when [TOML_ENABLE_WINDOWS_COMPAT](/libpalliate/generated/Files/toml_8hpp#define-toml-enable-windows-compat) is enabled.


### function parse_result

```cpp
inline TOML_NODISCARD_CTOR parse_result()
```

Default constructs an 'error' result. 

### function parse_result

```cpp
inline explicit TOML_NODISCARD_CTOR parse_result(
    toml::table && tbl
)
```


### function parse_result

```cpp
inline explicit TOML_NODISCARD_CTOR parse_result(
    parse_error && err
)
```


### function parse_result

```cpp
inline TOML_NODISCARD_CTOR parse_result(
    parse_result && res
)
```

Move constructor. 

### function operator=

```cpp
inline parse_result & operator=(
    parse_result && rhs
)
```

Move-assignment operator. 

### function ~parse_result

```cpp
inline ~parse_result()
```

Destructor. 

### function parse_result

```cpp
inline TOML_NODISCARD_CTOR parse_result()
```


### function parse_result

```cpp
inline explicit TOML_NODISCARD_CTOR parse_result(
    toml::table && tbl
)
```


### function parse_result

```cpp
inline explicit TOML_NODISCARD_CTOR parse_result(
    parse_error && err
)
```


### function parse_result

```cpp
inline TOML_NODISCARD_CTOR parse_result(
    parse_result && res
)
```


### function operator=

```cpp
inline parse_result & operator=(
    parse_result && rhs
)
```


### function ~parse_result

```cpp
inline ~parse_result()
```


### function succeeded

```cpp
inline TOML_NODISCARD bool succeeded() const
```


### function failed

```cpp
inline TOML_NODISCARD bool failed() const
```


### function operator bool

```cpp
inline explicit TOML_NODISCARD operator bool() const
```


### function table

```cpp
inline TOML_NODISCARD toml::table & table()
```


### function table

```cpp
inline TOML_NODISCARD toml::table && table()
```


### function table

```cpp
inline const TOML_NODISCARD toml::table & table() const
```


### function operator toml::table &

```cpp
inline TOML_NODISCARD operator toml::table &()
```


### function operator toml::table &&

```cpp
inline TOML_NODISCARD operator toml::table &&()
```


### function operator const toml::table &

```cpp
inline TOML_NODISCARD operator const toml::table &() const
```


### function error

```cpp
inline TOML_NODISCARD parse_error & error()
```


### function error

```cpp
inline TOML_NODISCARD parse_error && error()
```


### function error

```cpp
inline const TOML_NODISCARD parse_error & error() const
```


### function operator parse_error &

```cpp
inline explicit TOML_NODISCARD operator parse_error &()
```


### function operator parse_error &&

```cpp
inline explicit TOML_NODISCARD operator parse_error &&()
```


### function operator const parse_error &

```cpp
inline explicit TOML_NODISCARD operator const parse_error &() const
```


### function begin

```cpp
inline TOML_NODISCARDtable_iterator begin()
```


**Remark**: Always returns the same value as [end()](/libpalliate/generated/Classes/classparse__result#function-end) if parsing failed. 

### function begin

```cpp
inline TOML_NODISCARDconst_table_iterator begin() const
```


**Remark**: Always returns the same value as [end()](/libpalliate/generated/Classes/classparse__result#function-end) if parsing failed. 

### function cbegin

```cpp
inline TOML_NODISCARDconst_table_iterator cbegin() const
```


**Remark**: Always returns the same value as [cend()](/libpalliate/generated/Classes/classparse__result#function-cend) if parsing failed. 

### function end

```cpp
inline TOML_NODISCARDtable_iterator end()
```


### function end

```cpp
inline TOML_NODISCARDconst_table_iterator end() const
```


### function cend

```cpp
inline TOML_NODISCARDconst_table_iterator cend() const
```


### function operator[]

```cpp
inline TOML_NODISCARDnode_view< node > operator[](
    std::string_view key
)
```


**Parameters**: 

  * **key** The key used for the lookup.


**See**: toml::node_view 

**Return**: A view of the value at the given key if parsing was successful and a matching key existed, or an empty node view.

### function operator[]

```cpp
inline TOML_NODISCARDnode_view< const node > operator[](
    std::string_view key
) const
```


**Parameters**: 

  * **key** The key used for the lookup.


**See**: toml::node_view 

**Return**: A view of the value at the given key if parsing was successful and a matching key existed, or an empty node view.

### function at_path

```cpp
inline TOML_NODISCARDnode_view< node > at_path(
    std::string_view path
)
```


**See**: #toml::node::at_path(std::string_view) 

### function at_path

```cpp
inline TOML_NODISCARDnode_view< const node > at_path(
    std::string_view path
) const
```


**See**: #toml::node::at_path(std::string_view) 

## Friends

### friend operator<<

```cpp
friend std::ostream & operator<<(
    std::ostream & os,

    const parse_result & result
);
```

Prints the held error or table object out to a text stream. 

\availability This operator is only available when [TOML_ENABLE_FORMATTERS](/libpalliate/generated/Files/toml_8hpp#define-toml-enable-formatters) is enabled. 


### friend operator<<

```cpp
friend std::ostream & operator<<(
    std::ostream & os,

    const parse_result & result
);
```


\availability This operator is only available when [TOML_ENABLE_FORMATTERS](/libpalliate/generated/Files/toml_8hpp#define-toml-enable-formatters) is enabled. 



_Automatically updated on 2022-05-02 at 01:42:11 +0000._