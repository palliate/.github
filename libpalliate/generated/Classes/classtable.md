---
title: table
summary: A TOML table. 
parent: Classes
grand_parent: libpalliate
layout: default
---

# table



A TOML table.  [More...](#detailed-description)


`#include <toml.hpp>`

Inherits from node

## Public Types

|                | Name           |
| -------------- | -------------- |
| typedef toml::table_iterator | **[iterator](/libpalliate/generated/Classes/classtable#typedef-iterator)** <br>A BidirectionalIterator for iterating over key-value pairs in a toml::table.  |
| using [toml::const_table_iterator](/libpalliate/generated/Files/toml_8hpp#using-const-table-iterator) | **[const_iterator](/libpalliate/generated/Classes/classtable#using-const-iterator)** <br>A BidirectionalIterator for iterating over const key-value pairs in a toml::table.  |
| using [impl::unwrap_node](/libpalliate/generated/Files/toml_8hpp#using-unwrap-node)< ValueType > | **[unwrapped_type](/libpalliate/generated/Classes/classtable#using-unwrapped-type)**  |
| using toml::table_iterator | **[iterator](/libpalliate/generated/Classes/classtable#using-iterator)**  |
| using [toml::const_table_iterator](/libpalliate/generated/Files/toml_8hpp#using-const-table-iterator) | **[const_iterator](/libpalliate/generated/Classes/classtable#using-const-iterator)**  |
| using [impl::unwrap_node](/libpalliate/generated/Files/toml_8hpp#using-unwrap-node)< ValueType > | **[unwrapped_type](/libpalliate/generated/Classes/classtable#using-unwrapped-type)**  |

## Public Functions

|                | Name           |
| -------------- | -------------- |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter) node_type | **[type](/libpalliate/generated/Classes/classtable#function-type)**() const<br>Returns #toml::node_type::table.  |
| [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter)[TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) bool | **[is_homogeneous](/libpalliate/generated/Classes/classtable#function-is-homogeneous)**(node_type ntype) const |
| [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter)[TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) bool | **[is_homogeneous](/libpalliate/generated/Classes/classtable#function-is-homogeneous)**(node_type ntype, node *& first_nonmatch) |
| [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter)[TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) bool | **[is_homogeneous](/libpalliate/generated/Classes/classtable#function-is-homogeneous)**(node_type ntype, const node *& first_nonmatch) const |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter) bool | **[is_table](/libpalliate/generated/Classes/classtable#function-is-table)**() const<br>Returns `true`.  |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter) bool | **[is_array](/libpalliate/generated/Classes/classtable#function-is-array)**() const<br>Returns `false`.  |
| [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter) bool | **[is_array_of_tables](/libpalliate/generated/Classes/classtable#function-is-array-of-tables)**() const<br>Returns `false`.  |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter) bool | **[is_value](/libpalliate/generated/Classes/classtable#function-is-value)**() const<br>Returns `false`.  |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter) bool | **[is_string](/libpalliate/generated/Classes/classtable#function-is-string)**() const<br>Returns `false`.  |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter) bool | **[is_integer](/libpalliate/generated/Classes/classtable#function-is-integer)**() const<br>Returns `false`.  |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter) bool | **[is_floating_point](/libpalliate/generated/Classes/classtable#function-is-floating-point)**() const<br>Returns `false`.  |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter) bool | **[is_number](/libpalliate/generated/Classes/classtable#function-is-number)**() const<br>Returns `false`.  |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter) bool | **[is_boolean](/libpalliate/generated/Classes/classtable#function-is-boolean)**() const<br>Returns `false`.  |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter) bool | **[is_date](/libpalliate/generated/Classes/classtable#function-is-date)**() const<br>Returns `false`.  |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter) bool | **[is_time](/libpalliate/generated/Classes/classtable#function-is-time)**() const<br>Returns `false`.  |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter) bool | **[is_date_time](/libpalliate/generated/Classes/classtable#function-is-date-time)**() const<br>Returns `false`.  |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[table](/libpalliate/generated/Classes/classtable) * | **[as_table](/libpalliate/generated/Classes/classtable#function-as-table)**()<br>Returns a pointer to the table.  |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[array](/libpalliate/generated/Classes/classarray) * | **[as_array](/libpalliate/generated/Classes/classtable#function-as-array)**()<br>Returns `nullptr`.  |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< std::string > * | **[as_string](/libpalliate/generated/Classes/classtable#function-as-string)**()<br>Returns `nullptr`.  |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< int64_t > * | **[as_integer](/libpalliate/generated/Classes/classtable#function-as-integer)**()<br>Returns `nullptr`.  |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< double > * | **[as_floating_point](/libpalliate/generated/Classes/classtable#function-as-floating-point)**()<br>Returns `nullptr`.  |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< bool > * | **[as_boolean](/libpalliate/generated/Classes/classtable#function-as-boolean)**()<br>Returns `nullptr`.  |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< date > * | **[as_date](/libpalliate/generated/Classes/classtable#function-as-date)**()<br>Returns `nullptr`.  |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< [time](/libpalliate/generated/Classes/structtime) > * | **[as_time](/libpalliate/generated/Classes/classtable#function-as-time)**()<br>Returns `nullptr`.  |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< [date_time](/libpalliate/generated/Classes/structdate__time) > * | **[as_date_time](/libpalliate/generated/Classes/classtable#function-as-date-time)**()<br>Returns `nullptr`.  |
| const [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[table](/libpalliate/generated/Classes/classtable) * | **[as_table](/libpalliate/generated/Classes/classtable#function-as-table)**() const<br>Returns a const-qualified pointer to the table.  |
| const [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[array](/libpalliate/generated/Classes/classarray) * | **[as_array](/libpalliate/generated/Classes/classtable#function-as-array)**() const<br>Returns `nullptr`.  |
| const [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< std::string > * | **[as_string](/libpalliate/generated/Classes/classtable#function-as-string)**() const<br>Returns `nullptr`.  |
| const [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< int64_t > * | **[as_integer](/libpalliate/generated/Classes/classtable#function-as-integer)**() const<br>Returns `nullptr`.  |
| const [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< double > * | **[as_floating_point](/libpalliate/generated/Classes/classtable#function-as-floating-point)**() const<br>Returns `nullptr`.  |
| const [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< bool > * | **[as_boolean](/libpalliate/generated/Classes/classtable#function-as-boolean)**() const<br>Returns `nullptr`.  |
| const [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< date > * | **[as_date](/libpalliate/generated/Classes/classtable#function-as-date)**() const<br>Returns `nullptr`.  |
| const [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< [time](/libpalliate/generated/Classes/structtime) > * | **[as_time](/libpalliate/generated/Classes/classtable#function-as-time)**() const<br>Returns `nullptr`.  |
| const [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< [date_time](/libpalliate/generated/Classes/structdate__time) > * | **[as_date_time](/libpalliate/generated/Classes/classtable#function-as-date-time)**() const<br>Returns `nullptr`.  |
| [TOML_PURE_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-inline-getter) bool | **[is_inline](/libpalliate/generated/Classes/classtable#function-is-inline)**() const<br>Returns true if this table is an inline table.  |
| void | **[is_inline](/libpalliate/generated/Classes/classtable#function-is-inline)**(bool val)<br>Sets whether this table is a TOML inline table.  |
| [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter)[TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) node * | **[get](/libpalliate/generated/Classes/classtable#function-get)**(std::string_view key)<br>Gets the node at a specific key.  |
| const [TOML_PURE_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-inline-getter) node * | **[get](/libpalliate/generated/Classes/classtable#function-get)**(std::string_view key) const<br>Gets the node at a specific key (const overload).  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) node * | **[get](/libpalliate/generated/Classes/classtable#function-get)**(std::wstring_view key)<br>Gets the node at a specific key.  |
| const [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) node * | **[get](/libpalliate/generated/Classes/classtable#function-get)**(std::wstring_view key) const<br>Gets the node at a specific key (const overload).  |
| template <typename T \> <br>[TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter)[impl::wrap_node](/libpalliate/generated/Files/toml_8hpp#using-wrap-node)< T > * | **[get_as](/libpalliate/generated/Classes/classtable#function-get-as)**(std::string_view key)<br>Gets the node at a specific key if it is a particular type.  |
| template <typename T \> <br>const [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter)[impl::wrap_node](/libpalliate/generated/Files/toml_8hpp#using-wrap-node)< T > * | **[get_as](/libpalliate/generated/Classes/classtable#function-get-as)**(std::string_view key) const<br>Gets the node at a specific key if it is a particular type (const overload).  |
| template <typename T \> <br>[TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[impl::wrap_node](/libpalliate/generated/Files/toml_8hpp#using-wrap-node)< T > * | **[get_as](/libpalliate/generated/Classes/classtable#function-get-as)**(std::wstring_view key)<br>Gets the node at a specific key if it is a particular type.  |
| template <typename T \> <br>const [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[impl::wrap_node](/libpalliate/generated/Files/toml_8hpp#using-wrap-node)< T > * | **[get_as](/libpalliate/generated/Classes/classtable#function-get-as)**(std::wstring_view key) const<br>Gets the node at a specific key if it is a particular type (const overload).  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) node & | **[at](/libpalliate/generated/Classes/classtable#function-at)**(std::string_view key)<br>Gets a reference to the element at a specific key, throwing `std::out_of_range` if none existed.  |
| const [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) node & | **[at](/libpalliate/generated/Classes/classtable#function-at)**(std::string_view key) const<br>Gets a reference to the element at a specific key, throwing `std::out_of_range` if none existed.  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) node & | **[at](/libpalliate/generated/Classes/classtable#function-at)**(std::wstring_view key)<br>Gets a reference to the element at a specific key, throwing `std::out_of_range` if none existed.  |
| const [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) node & | **[at](/libpalliate/generated/Classes/classtable#function-at)**(std::wstring_view key) const<br>Gets a reference to the element at a specific key, throwing `std::out_of_range` if none existed.  |
| [TOML_PURE_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-inline-getter)[iterator](/libpalliate/generated/Classes/classtable#typedef-iterator) | **[begin](/libpalliate/generated/Classes/classtable#function-begin)**()<br>Returns an iterator to the first key-value pair.  |
| [TOML_PURE_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-inline-getter)[const_iterator](/libpalliate/generated/Classes/classtable#using-const-iterator) | **[begin](/libpalliate/generated/Classes/classtable#function-begin)**() const<br>Returns an iterator to the first key-value pair.  |
| [TOML_PURE_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-inline-getter)[const_iterator](/libpalliate/generated/Classes/classtable#using-const-iterator) | **[cbegin](/libpalliate/generated/Classes/classtable#function-cbegin)**() const<br>Returns an iterator to the first key-value pair.  |
| [TOML_PURE_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-inline-getter)[iterator](/libpalliate/generated/Classes/classtable#typedef-iterator) | **[end](/libpalliate/generated/Classes/classtable#function-end)**()<br>Returns an iterator to one-past-the-last key-value pair.  |
| [TOML_PURE_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-inline-getter)[const_iterator](/libpalliate/generated/Classes/classtable#using-const-iterator) | **[end](/libpalliate/generated/Classes/classtable#function-end)**() const<br>Returns an iterator to one-past-the-last key-value pair.  |
| [TOML_PURE_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-inline-getter)[const_iterator](/libpalliate/generated/Classes/classtable#using-const-iterator) | **[cend](/libpalliate/generated/Classes/classtable#function-cend)**() const<br>Returns an iterator to one-past-the-last key-value pair.  |
| [TOML_PURE_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-inline-getter) bool | **[empty](/libpalliate/generated/Classes/classtable#function-empty)**() const<br>Returns true if the table is empty.  |
| [TOML_PURE_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-inline-getter) size_t | **[size](/libpalliate/generated/Classes/classtable#function-size)**() const<br>Returns the number of key-value pairs in the table.  |
| [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter)[iterator](/libpalliate/generated/Classes/classtable#typedef-iterator) | **[lower_bound](/libpalliate/generated/Classes/classtable#function-lower-bound)**(std::string_view key)<br>Returns an iterator to the first key-value pair with key that is _not less_ than the given key.  |
| [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter)[const_iterator](/libpalliate/generated/Classes/classtable#using-const-iterator) | **[lower_bound](/libpalliate/generated/Classes/classtable#function-lower-bound)**(std::string_view key) const<br>Returns a const iterator to the first key-value pair with key that is _not less_ than the given key.  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[iterator](/libpalliate/generated/Classes/classtable#typedef-iterator) | **[lower_bound](/libpalliate/generated/Classes/classtable#function-lower-bound)**(std::wstring_view key)<br>Returns an iterator to the first key-value pair with key that is _not less_ than the given key.  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[const_iterator](/libpalliate/generated/Classes/classtable#using-const-iterator) | **[lower_bound](/libpalliate/generated/Classes/classtable#function-lower-bound)**(std::wstring_view key) const<br>Returns a const iterator to the first key-value pair with key that is _not less_ than the given key.  |
| [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter)[TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function)[iterator](/libpalliate/generated/Classes/classtable#typedef-iterator) | **[find](/libpalliate/generated/Classes/classtable#function-find)**(std::string_view key)<br>Gets an iterator to the node at a specific key.  |
| [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter)[TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function)[const_iterator](/libpalliate/generated/Classes/classtable#using-const-iterator) | **[find](/libpalliate/generated/Classes/classtable#function-find)**(std::string_view key) const<br>Gets an iterator to the node at a specific key (const overload)  |
| [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter) bool | **[contains](/libpalliate/generated/Classes/classtable#function-contains)**(std::string_view key) const<br>Returns true if the table contains a node at the given key.  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[iterator](/libpalliate/generated/Classes/classtable#typedef-iterator) | **[find](/libpalliate/generated/Classes/classtable#function-find)**(std::wstring_view key)<br>Gets an iterator to the node at a specific key.  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[const_iterator](/libpalliate/generated/Classes/classtable#using-const-iterator) | **[find](/libpalliate/generated/Classes/classtable#function-find)**(std::wstring_view key) const<br>Gets an iterator to the node at a specific key (const overload).  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) bool | **[contains](/libpalliate/generated/Classes/classtable#function-contains)**(std::wstring_view key) const<br>Returns true if the table contains a node at the given key.  |
| [iterator](/libpalliate/generated/Classes/classtable#typedef-iterator) | **[erase](/libpalliate/generated/Classes/classtable#function-erase)**([iterator](/libpalliate/generated/Classes/classtable#typedef-iterator) pos)<br>Removes the specified key-value pair from the table.  |
| [iterator](/libpalliate/generated/Classes/classtable#typedef-iterator) | **[erase](/libpalliate/generated/Classes/classtable#function-erase)**([const_iterator](/libpalliate/generated/Classes/classtable#using-const-iterator) pos)<br>Removes the specified key-value pair from the table (const iterator overload).  |
| [iterator](/libpalliate/generated/Classes/classtable#typedef-iterator) | **[erase](/libpalliate/generated/Classes/classtable#function-erase)**([const_iterator](/libpalliate/generated/Classes/classtable#using-const-iterator) begin, [const_iterator](/libpalliate/generated/Classes/classtable#using-const-iterator) end)<br>Removes the key-value pairs in the range [first, last) from the table.  |
| [TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) size_t | **[erase](/libpalliate/generated/Classes/classtable#function-erase)**(std::string_view key)<br>Removes the value with the given key from the table.  |
| size_t | **[erase](/libpalliate/generated/Classes/classtable#function-erase)**(std::wstring_view key)<br>Removes the value with the given key from the table.  |
| [TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function)[table](/libpalliate/generated/Classes/classtable) & | **[prune](/libpalliate/generated/Classes/classtable#function-prune)**(bool recursive =true)<br>Removes empty child arrays and tables.  |
| [table](/libpalliate/generated/Classes/classtable) && | **[prune](/libpalliate/generated/Classes/classtable#function-prune)**(bool recursive =true)<br>Removes empty child arrays and tables (rvalue overload).  |
| [TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) void | **[clear](/libpalliate/generated/Classes/classtable#function-clear)**()<br>Removes all key-value pairs from the table.  |
| | **[TOML_CONSTRAINED_TEMPLATE](/libpalliate/generated/Classes/classtable#function-toml-constrained-template)**(([is_key_or_convertible](/libpalliate/generated/Files/toml_8hpp#variable-is-key-or-convertible)< KeyType && >||[impl::is_wide_string](/libpalliate/generated/Files/toml_8hpp#variable-is-wide-string)< KeyType >) , typename ValueType , typename KeyType , typename... ValueArgs)<br>Emplaces a new value at a specific key if one did not already exist.  |
| constexpr | **[if](/libpalliate/generated/Classes/classtable#function-if)**([impl::is_wide_string](/libpalliate/generated/Files/toml_8hpp#variable-is-wide-string)< KeyType > ) |
| | **[if](/libpalliate/generated/Classes/classtable#function-if)**(![ipos](/libpalliate/generated/Classes/classtable#variable-ipos)-> second) |
| | **[TOML_CONSTRAINED_TEMPLATE](/libpalliate/generated/Classes/classtable#function-toml-constrained-template)**(([is_key_or_convertible](/libpalliate/generated/Files/toml_8hpp#variable-is-key-or-convertible)< KeyType && >||[impl::is_wide_string](/libpalliate/generated/Files/toml_8hpp#variable-is-wide-string)< KeyType >) , typename KeyType , typename ValueType )<br>Inserts a new value at a specific key if one did not already exist.  |
| void | **[insert](/libpalliate/generated/Classes/classtable#function-insert)**(Iter begin, Iter end, [value_flags](/libpalliate/generated/Files/toml_8hpp#variable-value-flags) flags =[preserve_source_value_flags](/libpalliate/generated/Files/toml_8hpp#variable-preserve-source-value-flags))<br>Inserts a series of key-value pairs into the table.  |
| | **[TOML_CONSTRAINED_TEMPLATE](/libpalliate/generated/Classes/classtable#function-toml-constrained-template)**(([is_key_or_convertible](/libpalliate/generated/Files/toml_8hpp#variable-is-key-or-convertible)< KeyType && >||[impl::is_wide_string](/libpalliate/generated/Files/toml_8hpp#variable-is-wide-string)< KeyType >) , typename KeyType , typename ValueType )<br>Inserts or assigns a value at a specific key.  |
| | **[TOML_CONSTRAINED_TEMPLATE](/libpalliate/generated/Classes/classtable#function-toml-constrained-template)**(([is_key_or_convertible](/libpalliate/generated/Files/toml_8hpp#variable-is-key-or-convertible)< KeyType && >||[impl::is_wide_string](/libpalliate/generated/Files/toml_8hpp#variable-is-wide-string)< KeyType >) , typename ValueType , typename KeyType , typename... ValueArgs)<br>Emplaces a new value at a specific key if one did not already exist.  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[node_view](/libpalliate/generated/Classes/classnode__view)< node > | **[operator[]](/libpalliate/generated/Classes/classtable#function-operator[])**(std::string_view key)<br>Gets a [node_view]() for the selected value.  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[node_view](/libpalliate/generated/Classes/classnode__view)< const node > | **[operator[]](/libpalliate/generated/Classes/classtable#function-operator[])**(std::string_view key) const<br>Gets a [node_view]() for the selected value (const overload).  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[node_view](/libpalliate/generated/Classes/classnode__view)< node > | **[operator[]](/libpalliate/generated/Classes/classtable#function-operator[])**(std::wstring_view key)<br>Gets a [node_view]() for the selected value.  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[node_view](/libpalliate/generated/Classes/classnode__view)< const node > | **[operator[]](/libpalliate/generated/Classes/classtable#function-operator[])**(std::wstring_view key) const<br>Gets a [node_view]() for the selected value (const overload).  |
| [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor)[TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) | **[table](/libpalliate/generated/Classes/classtable#function-table)**()<br>Default constructor.  |
| [TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) | **[~table](/libpalliate/generated/Classes/classtable#function-~table)**() |
| [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor)[TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) | **[table](/libpalliate/generated/Classes/classtable#function-table)**(const [table](/libpalliate/generated/Classes/classtable) & )<br>Copy constructor.  |
| [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor)[TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) | **[table](/libpalliate/generated/Classes/classtable#function-table)**([table](/libpalliate/generated/Classes/classtable) && other)<br>Move constructor.  |
| [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor)[TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) | **[table](/libpalliate/generated/Classes/classtable#function-table)**(std::initializer_list< impl::table_init_pair > kvps)<br>Constructs a table with one or more initial key-value pairs.  |
| [TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function)[table](/libpalliate/generated/Classes/classtable) & | **[operator=](/libpalliate/generated/Classes/classtable#function-operator=)**(const [table](/libpalliate/generated/Classes/classtable) & )<br>Copy-assignment operator.  |
| [TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function)[table](/libpalliate/generated/Classes/classtable) & | **[operator=](/libpalliate/generated/Classes/classtable#function-operator=)**([table](/libpalliate/generated/Classes/classtable) && rhs)<br>Move-assignment operator.  |
| [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor)[TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) | **[table](/libpalliate/generated/Classes/classtable#function-table)**() |
| [TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) | **[~table](/libpalliate/generated/Classes/classtable#function-~table)**() |
| [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor)[TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) | **[table](/libpalliate/generated/Classes/classtable#function-table)**(const [table](/libpalliate/generated/Classes/classtable) & ) |
| [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor)[TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) | **[table](/libpalliate/generated/Classes/classtable#function-table)**([table](/libpalliate/generated/Classes/classtable) && other) |
| [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor)[TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) | **[table](/libpalliate/generated/Classes/classtable#function-table)**(std::initializer_list< impl::table_init_pair > kvps) |
| [TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function)[table](/libpalliate/generated/Classes/classtable) & | **[operator=](/libpalliate/generated/Classes/classtable#function-operator=)**(const [table](/libpalliate/generated/Classes/classtable) & ) |
| [TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function)[table](/libpalliate/generated/Classes/classtable) & | **[operator=](/libpalliate/generated/Classes/classtable#function-operator=)**([table](/libpalliate/generated/Classes/classtable) && rhs) |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter) node_type | **[type](/libpalliate/generated/Classes/classtable#function-type)**() const |
| [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter)[TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) bool | **[is_homogeneous](/libpalliate/generated/Classes/classtable#function-is-homogeneous)**(node_type ntype) const |
| [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter)[TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) bool | **[is_homogeneous](/libpalliate/generated/Classes/classtable#function-is-homogeneous)**(node_type ntype, node *& first_nonmatch) |
| [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter)[TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) bool | **[is_homogeneous](/libpalliate/generated/Classes/classtable#function-is-homogeneous)**(node_type ntype, const node *& first_nonmatch) const |
| template <typename ElemType  =void\> <br>[TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter) bool | **[is_homogeneous](/libpalliate/generated/Classes/classtable#function-is-homogeneous)**() const |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter) bool | **[is_table](/libpalliate/generated/Classes/classtable#function-is-table)**() const |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter) bool | **[is_array](/libpalliate/generated/Classes/classtable#function-is-array)**() const |
| [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter) bool | **[is_array_of_tables](/libpalliate/generated/Classes/classtable#function-is-array-of-tables)**() const |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter) bool | **[is_value](/libpalliate/generated/Classes/classtable#function-is-value)**() const |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter) bool | **[is_string](/libpalliate/generated/Classes/classtable#function-is-string)**() const |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter) bool | **[is_integer](/libpalliate/generated/Classes/classtable#function-is-integer)**() const |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter) bool | **[is_floating_point](/libpalliate/generated/Classes/classtable#function-is-floating-point)**() const |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter) bool | **[is_number](/libpalliate/generated/Classes/classtable#function-is-number)**() const |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter) bool | **[is_boolean](/libpalliate/generated/Classes/classtable#function-is-boolean)**() const |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter) bool | **[is_date](/libpalliate/generated/Classes/classtable#function-is-date)**() const |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter) bool | **[is_time](/libpalliate/generated/Classes/classtable#function-is-time)**() const |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter) bool | **[is_date_time](/libpalliate/generated/Classes/classtable#function-is-date-time)**() const |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[table](/libpalliate/generated/Classes/classtable) * | **[as_table](/libpalliate/generated/Classes/classtable#function-as-table)**() |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[array](/libpalliate/generated/Classes/classarray) * | **[as_array](/libpalliate/generated/Classes/classtable#function-as-array)**() |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< std::string > * | **[as_string](/libpalliate/generated/Classes/classtable#function-as-string)**() |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< int64_t > * | **[as_integer](/libpalliate/generated/Classes/classtable#function-as-integer)**() |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< double > * | **[as_floating_point](/libpalliate/generated/Classes/classtable#function-as-floating-point)**() |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< bool > * | **[as_boolean](/libpalliate/generated/Classes/classtable#function-as-boolean)**() |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< date > * | **[as_date](/libpalliate/generated/Classes/classtable#function-as-date)**() |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< [time](/libpalliate/generated/Classes/structtime) > * | **[as_time](/libpalliate/generated/Classes/classtable#function-as-time)**() |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< [date_time](/libpalliate/generated/Classes/structdate__time) > * | **[as_date_time](/libpalliate/generated/Classes/classtable#function-as-date-time)**() |
| const [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[table](/libpalliate/generated/Classes/classtable) * | **[as_table](/libpalliate/generated/Classes/classtable#function-as-table)**() const |
| const [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[array](/libpalliate/generated/Classes/classarray) * | **[as_array](/libpalliate/generated/Classes/classtable#function-as-array)**() const |
| const [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< std::string > * | **[as_string](/libpalliate/generated/Classes/classtable#function-as-string)**() const |
| const [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< int64_t > * | **[as_integer](/libpalliate/generated/Classes/classtable#function-as-integer)**() const |
| const [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< double > * | **[as_floating_point](/libpalliate/generated/Classes/classtable#function-as-floating-point)**() const |
| const [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< bool > * | **[as_boolean](/libpalliate/generated/Classes/classtable#function-as-boolean)**() const |
| const [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< date > * | **[as_date](/libpalliate/generated/Classes/classtable#function-as-date)**() const |
| const [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< [time](/libpalliate/generated/Classes/structtime) > * | **[as_time](/libpalliate/generated/Classes/classtable#function-as-time)**() const |
| const [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< [date_time](/libpalliate/generated/Classes/structdate__time) > * | **[as_date_time](/libpalliate/generated/Classes/classtable#function-as-date-time)**() const |
| [TOML_PURE_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-inline-getter) bool | **[is_inline](/libpalliate/generated/Classes/classtable#function-is-inline)**() const |
| void | **[is_inline](/libpalliate/generated/Classes/classtable#function-is-inline)**(bool val) |
| [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter)[TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) node * | **[get](/libpalliate/generated/Classes/classtable#function-get)**(std::string_view key) |
| const [TOML_PURE_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-inline-getter) node * | **[get](/libpalliate/generated/Classes/classtable#function-get)**(std::string_view key) const |
| template <typename T \> <br>[TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter)[impl::wrap_node](/libpalliate/generated/Files/toml_8hpp#using-wrap-node)< T > * | **[get_as](/libpalliate/generated/Classes/classtable#function-get-as)**(std::string_view key) |
| template <typename T \> <br>const [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter)[impl::wrap_node](/libpalliate/generated/Files/toml_8hpp#using-wrap-node)< T > * | **[get_as](/libpalliate/generated/Classes/classtable#function-get-as)**(std::string_view key) const |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) node & | **[at](/libpalliate/generated/Classes/classtable#function-at)**(std::string_view key) |
| const [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) node & | **[at](/libpalliate/generated/Classes/classtable#function-at)**(std::string_view key) const |
| [TOML_PURE_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-inline-getter)[iterator](/libpalliate/generated/Classes/classtable#typedef-iterator) | **[begin](/libpalliate/generated/Classes/classtable#function-begin)**() |
| [TOML_PURE_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-inline-getter)[const_iterator](/libpalliate/generated/Classes/classtable#using-const-iterator) | **[begin](/libpalliate/generated/Classes/classtable#function-begin)**() const |
| [TOML_PURE_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-inline-getter)[const_iterator](/libpalliate/generated/Classes/classtable#using-const-iterator) | **[cbegin](/libpalliate/generated/Classes/classtable#function-cbegin)**() const |
| [TOML_PURE_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-inline-getter)[iterator](/libpalliate/generated/Classes/classtable#typedef-iterator) | **[end](/libpalliate/generated/Classes/classtable#function-end)**() |
| [TOML_PURE_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-inline-getter)[const_iterator](/libpalliate/generated/Classes/classtable#using-const-iterator) | **[end](/libpalliate/generated/Classes/classtable#function-end)**() const |
| [TOML_PURE_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-inline-getter)[const_iterator](/libpalliate/generated/Classes/classtable#using-const-iterator) | **[cend](/libpalliate/generated/Classes/classtable#function-cend)**() const |
| [TOML_PURE_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-inline-getter) bool | **[empty](/libpalliate/generated/Classes/classtable#function-empty)**() const |
| [TOML_PURE_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-inline-getter) size_t | **[size](/libpalliate/generated/Classes/classtable#function-size)**() const |
| [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter)[iterator](/libpalliate/generated/Classes/classtable#typedef-iterator) | **[lower_bound](/libpalliate/generated/Classes/classtable#function-lower-bound)**(std::string_view key) |
| [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter)[const_iterator](/libpalliate/generated/Classes/classtable#using-const-iterator) | **[lower_bound](/libpalliate/generated/Classes/classtable#function-lower-bound)**(std::string_view key) const |
| [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter)[TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function)[iterator](/libpalliate/generated/Classes/classtable#typedef-iterator) | **[find](/libpalliate/generated/Classes/classtable#function-find)**(std::string_view key) |
| [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter)[TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function)[const_iterator](/libpalliate/generated/Classes/classtable#using-const-iterator) | **[find](/libpalliate/generated/Classes/classtable#function-find)**(std::string_view key) const |
| [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter) bool | **[contains](/libpalliate/generated/Classes/classtable#function-contains)**(std::string_view key) const |
| [iterator](/libpalliate/generated/Classes/classtable#typedef-iterator) | **[erase](/libpalliate/generated/Classes/classtable#function-erase)**([iterator](/libpalliate/generated/Classes/classtable#typedef-iterator) pos) |
| [iterator](/libpalliate/generated/Classes/classtable#typedef-iterator) | **[erase](/libpalliate/generated/Classes/classtable#function-erase)**([const_iterator](/libpalliate/generated/Classes/classtable#using-const-iterator) pos) |
| [iterator](/libpalliate/generated/Classes/classtable#typedef-iterator) | **[erase](/libpalliate/generated/Classes/classtable#function-erase)**([const_iterator](/libpalliate/generated/Classes/classtable#using-const-iterator) begin, [const_iterator](/libpalliate/generated/Classes/classtable#using-const-iterator) end) |
| [TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) size_t | **[erase](/libpalliate/generated/Classes/classtable#function-erase)**(std::string_view key) |
| [TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function)[table](/libpalliate/generated/Classes/classtable) & | **[prune](/libpalliate/generated/Classes/classtable#function-prune)**(bool recursive =true) |
| [table](/libpalliate/generated/Classes/classtable) && | **[prune](/libpalliate/generated/Classes/classtable#function-prune)**(bool recursive =true) |
| [TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) void | **[clear](/libpalliate/generated/Classes/classtable#function-clear)**() |
| | **[TOML_CONSTRAINED_TEMPLATE](/libpalliate/generated/Classes/classtable#function-toml-constrained-template)**(([is_key_or_convertible](/libpalliate/generated/Files/toml_8hpp#variable-is-key-or-convertible)< KeyType && >||[impl::is_wide_string](/libpalliate/generated/Files/toml_8hpp#variable-is-wide-string)< KeyType >) , typename ValueType , typename KeyType , typename... ValueArgs) |
| constexpr | **[if](/libpalliate/generated/Classes/classtable#function-if)**([impl::is_wide_string](/libpalliate/generated/Files/toml_8hpp#variable-is-wide-string)< KeyType > ) |
| | **[if](/libpalliate/generated/Classes/classtable#function-if)**(![ipos](/libpalliate/generated/Classes/classtable#variable-ipos)-> second) |
| | **[TOML_CONSTRAINED_TEMPLATE](/libpalliate/generated/Classes/classtable#function-toml-constrained-template)**(([is_key_or_convertible](/libpalliate/generated/Files/toml_8hpp#variable-is-key-or-convertible)< KeyType && >||[impl::is_wide_string](/libpalliate/generated/Files/toml_8hpp#variable-is-wide-string)< KeyType >) , typename KeyType , typename ValueType ) |
| void | **[insert](/libpalliate/generated/Classes/classtable#function-insert)**(Iter begin, Iter end, [value_flags](/libpalliate/generated/Files/toml_8hpp#variable-value-flags) flags =[preserve_source_value_flags](/libpalliate/generated/Files/toml_8hpp#variable-preserve-source-value-flags)) |
| | **[TOML_CONSTRAINED_TEMPLATE](/libpalliate/generated/Classes/classtable#function-toml-constrained-template)**(([is_key_or_convertible](/libpalliate/generated/Files/toml_8hpp#variable-is-key-or-convertible)< KeyType && >||[impl::is_wide_string](/libpalliate/generated/Files/toml_8hpp#variable-is-wide-string)< KeyType >) , typename KeyType , typename ValueType ) |
| | **[TOML_CONSTRAINED_TEMPLATE](/libpalliate/generated/Classes/classtable#function-toml-constrained-template)**(([is_key_or_convertible](/libpalliate/generated/Files/toml_8hpp#variable-is-key-or-convertible)< KeyType && >||[impl::is_wide_string](/libpalliate/generated/Files/toml_8hpp#variable-is-wide-string)< KeyType >) , typename ValueType , typename KeyType , typename... ValueArgs) |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[node_view](/libpalliate/generated/Classes/classnode__view)< node > | **[operator[]](/libpalliate/generated/Classes/classtable#function-operator[])**(std::string_view key) |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[node_view](/libpalliate/generated/Classes/classnode__view)< const node > | **[operator[]](/libpalliate/generated/Classes/classtable#function-operator[])**(std::string_view key) const |

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| KeyType && | **[key](/libpalliate/generated/Classes/classtable#variable-key)**  |
| KeyType ValueArgs && | **[args](/libpalliate/generated/Classes/classtable#variable-args)**  |
| | **[else](/libpalliate/generated/Classes/classtable#variable-else)**  |
| map_iterator | **[ipos](/libpalliate/generated/Classes/classtable#variable-ipos)**  |
| toml::table_iterator | **[iterator](/libpalliate/generated/Classes/classtable#variable-iterator)**  |

## Friends

|                | Name           |
| -------------- | -------------- |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) friend bool | **[operator==](/libpalliate/generated/Classes/classtable#friend-operator==)**(const [table](/libpalliate/generated/Classes/classtable) & lhs, const [table](/libpalliate/generated/Classes/classtable) & rhs) <br>Equality operator.  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) friend bool | **[operator!=](/libpalliate/generated/Classes/classtable#friend-operator!=)**(const [table](/libpalliate/generated/Classes/classtable) & lhs, const [table](/libpalliate/generated/Classes/classtable) & rhs) <br>Inequality operator.  |
| std::ostream & | **[operator<<](/libpalliate/generated/Classes/classtable#friend-operator<<)**(std::ostream & lhs, const [table](/libpalliate/generated/Classes/classtable) & rhs) <br>Prints the table out to a stream as formatted TOML.  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) friend bool | **[operator==](/libpalliate/generated/Classes/classtable#friend-operator==)**(const [table](/libpalliate/generated/Classes/classtable) & lhs, const [table](/libpalliate/generated/Classes/classtable) & rhs)  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) friend bool | **[operator!=](/libpalliate/generated/Classes/classtable#friend-operator!=)**(const [table](/libpalliate/generated/Classes/classtable) & lhs, const [table](/libpalliate/generated/Classes/classtable) & rhs)  |
| std::ostream & | **[operator<<](/libpalliate/generated/Classes/classtable#friend-operator<<)**(std::ostream & lhs, const [table](/libpalliate/generated/Classes/classtable) & rhs)  |

## Detailed Description

```cpp
class table;
```

A TOML table. 

\detail The interface of this type is modeled after std::map, with some additional considerations made for the heterogeneous nature of a TOML table.

\cpp toml::table tbl = toml::parse(R"( 

```
[animals]
cats = [ "tiger", "lion", "puma" ]
birds = [ "macaw", "pigeon", "canary" ]
fish = [ "salmon", "trout", "carp" ]
```

)"sv);

// operator[] retrieves node-views std::cout << "cats: " << tbl["animals"]["cats"] << "\n"; std::cout << "fish[1]: " << tbl["animals"]["fish"][1] << "\n";

// [at_path()](/libpalliate/generated/Files/at__path_8h#function-at-path) does fully-qualified "toml path" lookups std::cout << "cats: " << tbl.at_path("animals.cats") << "\n"; std::cout << "fish[1]: " << tbl.at_path("animals.fish[1]") << "\n"; \ecpp

\out cats: ['tiger', 'lion', 'puma'] fish[1] : 'trout' cats : ['tiger', 'lion', 'puma'] fish[1] : 'trout' \eout 

## Public Types Documentation

### typedef iterator

```cpp
return table::iterator;
```

A BidirectionalIterator for iterating over key-value pairs in a toml::table. 

### using const_iterator

```cpp
using table::const_iterator =  toml::const_table_iterator;
```

A BidirectionalIterator for iterating over const key-value pairs in a toml::table. 

### using unwrapped_type

```cpp
using table::unwrapped_type =  impl::unwrap_node<ValueType>;
```


### using iterator

```cpp
using table::iterator =  toml::table_iterator;
```


### using const_iterator

```cpp
using table::const_iterator =  toml::const_table_iterator;
```


### using unwrapped_type

```cpp
using table::unwrapped_type =  impl::unwrap_node<ValueType>;
```


## Public Functions Documentation

### function type

```cpp
inline TOML_CONST_INLINE_GETTER node_type type() const
```

Returns #toml::node_type::table. 

### function is_homogeneous

```cpp
TOML_PURE_GETTERTOML_EXPORTED_MEMBER_FUNCTION bool is_homogeneous(
    node_type ntype
) const
```


### function is_homogeneous

```cpp
TOML_PURE_GETTERTOML_EXPORTED_MEMBER_FUNCTION bool is_homogeneous(
    node_type ntype,
    node *& first_nonmatch
)
```


### function is_homogeneous

```cpp
TOML_PURE_GETTERTOML_EXPORTED_MEMBER_FUNCTION bool is_homogeneous(
    node_type ntype,
    const node *& first_nonmatch
) const
```


### function is_table

```cpp
inline TOML_CONST_INLINE_GETTER bool is_table() const
```

Returns `true`. 

### function is_array

```cpp
inline TOML_CONST_INLINE_GETTER bool is_array() const
```

Returns `false`. 

### function is_array_of_tables

```cpp
inline TOML_PURE_GETTER bool is_array_of_tables() const
```

Returns `false`. 

### function is_value

```cpp
inline TOML_CONST_INLINE_GETTER bool is_value() const
```

Returns `false`. 

### function is_string

```cpp
inline TOML_CONST_INLINE_GETTER bool is_string() const
```

Returns `false`. 

### function is_integer

```cpp
inline TOML_CONST_INLINE_GETTER bool is_integer() const
```

Returns `false`. 

### function is_floating_point

```cpp
inline TOML_CONST_INLINE_GETTER bool is_floating_point() const
```

Returns `false`. 

### function is_number

```cpp
inline TOML_CONST_INLINE_GETTER bool is_number() const
```

Returns `false`. 

### function is_boolean

```cpp
inline TOML_CONST_INLINE_GETTER bool is_boolean() const
```

Returns `false`. 

### function is_date

```cpp
inline TOML_CONST_INLINE_GETTER bool is_date() const
```

Returns `false`. 

### function is_time

```cpp
inline TOML_CONST_INLINE_GETTER bool is_time() const
```

Returns `false`. 

### function is_date_time

```cpp
inline TOML_CONST_INLINE_GETTER bool is_date_time() const
```

Returns `false`. 

### function as_table

```cpp
inline TOML_CONST_INLINE_GETTERtable * as_table()
```

Returns a pointer to the table. 

### function as_array

```cpp
inline TOML_CONST_INLINE_GETTERarray * as_array()
```

Returns `nullptr`. 

### function as_string

```cpp
inline TOML_CONST_INLINE_GETTERtoml::value< std::string > * as_string()
```

Returns `nullptr`. 

### function as_integer

```cpp
inline TOML_CONST_INLINE_GETTERtoml::value< int64_t > * as_integer()
```

Returns `nullptr`. 

### function as_floating_point

```cpp
inline TOML_CONST_INLINE_GETTERtoml::value< double > * as_floating_point()
```

Returns `nullptr`. 

### function as_boolean

```cpp
inline TOML_CONST_INLINE_GETTERtoml::value< bool > * as_boolean()
```

Returns `nullptr`. 

### function as_date

```cpp
inline TOML_CONST_INLINE_GETTERtoml::value< date > * as_date()
```

Returns `nullptr`. 

### function as_time

```cpp
inline TOML_CONST_INLINE_GETTERtoml::value< time > * as_time()
```

Returns `nullptr`. 

### function as_date_time

```cpp
inline TOML_CONST_INLINE_GETTERtoml::value< date_time > * as_date_time()
```

Returns `nullptr`. 

### function as_table

```cpp
inline const TOML_CONST_INLINE_GETTERtable * as_table() const
```

Returns a const-qualified pointer to the table. 

### function as_array

```cpp
inline const TOML_CONST_INLINE_GETTERarray * as_array() const
```

Returns `nullptr`. 

### function as_string

```cpp
inline const TOML_CONST_INLINE_GETTERtoml::value< std::string > * as_string() const
```

Returns `nullptr`. 

### function as_integer

```cpp
inline const TOML_CONST_INLINE_GETTERtoml::value< int64_t > * as_integer() const
```

Returns `nullptr`. 

### function as_floating_point

```cpp
inline const TOML_CONST_INLINE_GETTERtoml::value< double > * as_floating_point() const
```

Returns `nullptr`. 

### function as_boolean

```cpp
inline const TOML_CONST_INLINE_GETTERtoml::value< bool > * as_boolean() const
```

Returns `nullptr`. 

### function as_date

```cpp
inline const TOML_CONST_INLINE_GETTERtoml::value< date > * as_date() const
```

Returns `nullptr`. 

### function as_time

```cpp
inline const TOML_CONST_INLINE_GETTERtoml::value< time > * as_time() const
```

Returns `nullptr`. 

### function as_date_time

```cpp
inline const TOML_CONST_INLINE_GETTERtoml::value< date_time > * as_date_time() const
```

Returns `nullptr`. 

### function is_inline

```cpp
inline TOML_PURE_INLINE_GETTER bool is_inline() const
```

Returns true if this table is an inline table. 

**Remark**: Runtime-constructed tables (i.e. those not created during parsing) are not inline by default. 

### function is_inline

```cpp
inline void is_inline(
    bool val
)
```

Sets whether this table is a TOML inline table. 

**Parameters**: 

  * **val** The new value for 'inline'. 


**Remark**: A table being 'inline' is only relevent during printing; it has no effect on the general functionality of the table object.

\detail \godbolt{an9xdj}

\cpp auto tbl = toml::table{ { "a", 1 }, { "b", 2 }, { "c", 3 }, { "d", toml::table{ { "e", 4 } } } }; std::cout << "is inline? "sv << tbl.is_inline() << "\n"; std::cout << tbl << "\n\n";

tbl.is_inline(!tbl.[is_inline()](/libpalliate/generated/Classes/classtable#function-is-inline)); std::cout << "is inline? "sv << tbl.is_inline() << "\n"; std::cout << tbl << "\n"; \ecpp

\out is inline? false a = 1 b = 2 c = 3

[d] e = 4

is inline? true { a = 1, b = 2, c = 3, d = { e = 4 } } \eout


### function get

```cpp
TOML_PURE_GETTERTOML_EXPORTED_MEMBER_FUNCTION node * get(
    std::string_view key
)
```

Gets the node at a specific key. 

**Parameters**: 

  * **key** The node's key.


**Return**: A pointer to the node at the specified key, or nullptr. 

\detail \cpp auto tbl = toml::table{ { "a", 42, }, { "b", "is the meaning of life, apparently." } }; std::cout << R"(node ["a"] exists: )"sv << !!arr.get("a") << "\n"; std::cout << R"(node ["b"] exists: )"sv << !!arr.get("b") << "\n"; std::cout << R"(node ["c"] exists: )"sv << !!arr.get("c") << "\n"; if (auto val = arr.get("a")) std::cout << R"(node ["a"] was an )"sv << val->[type()](/libpalliate/generated/Classes/classtable#function-type) << "\n"; \ecpp

\out node ["a"] exists: true node ["b"] exists: true node ["c"] exists: false node ["a"] was an integer \eout


### function get

```cpp
inline const TOML_PURE_INLINE_GETTER node * get(
    std::string_view key
) const
```

Gets the node at a specific key (const overload). 

**Parameters**: 

  * **key** The node's key.


**Return**: A pointer to the node at the specified key, or nullptr. 

### function get

```cpp
inline TOML_NODISCARD node * get(
    std::wstring_view key
)
```

Gets the node at a specific key. 

**Parameters**: 

  * **key** The node's key.


**Return**: A pointer to the node at the specified key, or nullptr. 

\availability This overload is only available when [TOML_ENABLE_WINDOWS_COMPAT](/libpalliate/generated/Files/toml_8hpp#define-toml-enable-windows-compat) is enabled.


### function get

```cpp
inline const TOML_NODISCARD node * get(
    std::wstring_view key
) const
```

Gets the node at a specific key (const overload). 

**Parameters**: 

  * **key** The node's key.


**Return**: A pointer to the node at the specified key, or nullptr. 

\availability This overload is only available when [TOML_ENABLE_WINDOWS_COMPAT](/libpalliate/generated/Files/toml_8hpp#define-toml-enable-windows-compat) is enabled.


### function get_as

```cpp
template <typename T >
inline TOML_PURE_GETTERimpl::wrap_node< T > * get_as(
    std::string_view key
)
```

Gets the node at a specific key if it is a particular type. 

**Parameters**: 

  * **key** The node's key.


**Template Parameters**: 

  * **T** One of the TOML node or value types. 


**Return**: A pointer to the node at the specified key if it was of the given type, or nullptr. 

\detail \cpp auto tbl = toml::table{ { "a", 42, }, { "b", "is the meaning of life, apparently." } }; if (auto val = arr.get_as<int64_t>("a")) std::cout << R"(node ["a"] was an integer with value )"sv << **val << "\n"; \ecpp

\out node ["a"] was an integer with value 42 \eout


### function get_as

```cpp
template <typename T >
inline const TOML_PURE_GETTERimpl::wrap_node< T > * get_as(
    std::string_view key
) const
```

Gets the node at a specific key if it is a particular type (const overload). 

**Parameters**: 

  * **key** The node's key.


**Template Parameters**: 

  * **T** One of the TOML node or value types. 


**Return**: A pointer to the node at the specified key if it was of the given type, or nullptr. 

### function get_as

```cpp
template <typename T >
inline TOML_NODISCARDimpl::wrap_node< T > * get_as(
    std::wstring_view key
)
```

Gets the node at a specific key if it is a particular type. 

**Parameters**: 

  * **key** The node's key.


**Template Parameters**: 

  * **T** One of the TOML node or value types. 


**Return**: A pointer to the node at the specified key if it was of the given type, or nullptr. 

\availability This overload is only available when [TOML_ENABLE_WINDOWS_COMPAT](/libpalliate/generated/Files/toml_8hpp#define-toml-enable-windows-compat) is enabled.


### function get_as

```cpp
template <typename T >
inline const TOML_NODISCARDimpl::wrap_node< T > * get_as(
    std::wstring_view key
) const
```

Gets the node at a specific key if it is a particular type (const overload). 

**Parameters**: 

  * **key** The node's key.


**Template Parameters**: 

  * **T** One of the TOML node or value types. 


**Return**: A pointer to the node at the specified key if it was of the given type, or nullptr. 

\availability This overload is only available when [TOML_ENABLE_WINDOWS_COMPAT](/libpalliate/generated/Files/toml_8hpp#define-toml-enable-windows-compat) is enabled.


### function at

```cpp
TOML_NODISCARDTOML_EXPORTED_MEMBER_FUNCTION node & at(
    std::string_view key
)
```

Gets a reference to the element at a specific key, throwing `std::out_of_range` if none existed. 

### function at

```cpp
inline const TOML_NODISCARD node & at(
    std::string_view key
) const
```

Gets a reference to the element at a specific key, throwing `std::out_of_range` if none existed. 

### function at

```cpp
inline TOML_NODISCARD node & at(
    std::wstring_view key
)
```

Gets a reference to the element at a specific key, throwing `std::out_of_range` if none existed. 

\availability This overload is only available when [TOML_ENABLE_WINDOWS_COMPAT](/libpalliate/generated/Files/toml_8hpp#define-toml-enable-windows-compat) is enabled. 


### function at

```cpp
inline const TOML_NODISCARD node & at(
    std::wstring_view key
) const
```

Gets a reference to the element at a specific key, throwing `std::out_of_range` if none existed. 

\availability This overload is only available when [TOML_ENABLE_WINDOWS_COMPAT](/libpalliate/generated/Files/toml_8hpp#define-toml-enable-windows-compat) is enabled. 


### function begin

```cpp
inline TOML_PURE_INLINE_GETTERiterator begin()
```

Returns an iterator to the first key-value pair. 

### function begin

```cpp
inline TOML_PURE_INLINE_GETTERconst_iterator begin() const
```

Returns an iterator to the first key-value pair. 

### function cbegin

```cpp
inline TOML_PURE_INLINE_GETTERconst_iterator cbegin() const
```

Returns an iterator to the first key-value pair. 

### function end

```cpp
inline TOML_PURE_INLINE_GETTERiterator end()
```

Returns an iterator to one-past-the-last key-value pair. 

### function end

```cpp
inline TOML_PURE_INLINE_GETTERconst_iterator end() const
```

Returns an iterator to one-past-the-last key-value pair. 

### function cend

```cpp
inline TOML_PURE_INLINE_GETTERconst_iterator cend() const
```

Returns an iterator to one-past-the-last key-value pair. 

### function empty

```cpp
inline TOML_PURE_INLINE_GETTER bool empty() const
```

Returns true if the table is empty. 

### function size

```cpp
inline TOML_PURE_INLINE_GETTER size_t size() const
```

Returns the number of key-value pairs in the table. 

### function lower_bound

```cpp
inline TOML_PURE_GETTERiterator lower_bound(
    std::string_view key
)
```

Returns an iterator to the first key-value pair with key that is _not less_ than the given key. 

**Return**: An iterator to the first matching key-value pair, or [end()](/libpalliate/generated/Classes/classtable#function-end). 

### function lower_bound

```cpp
inline TOML_PURE_GETTERconst_iterator lower_bound(
    std::string_view key
) const
```

Returns a const iterator to the first key-value pair with key that is _not less_ than the given key. 

**Return**: An iterator to the first matching key-value pair, or [end()](/libpalliate/generated/Classes/classtable#function-end). 

### function lower_bound

```cpp
inline TOML_NODISCARDiterator lower_bound(
    std::wstring_view key
)
```

Returns an iterator to the first key-value pair with key that is _not less_ than the given key. 

**Return**: An iterator to the first matching key-value pair, or [end()](/libpalliate/generated/Classes/classtable#function-end). 

\availability This overload is only available when [TOML_ENABLE_WINDOWS_COMPAT](/libpalliate/generated/Files/toml_8hpp#define-toml-enable-windows-compat) is enabled.


### function lower_bound

```cpp
inline TOML_NODISCARDconst_iterator lower_bound(
    std::wstring_view key
) const
```

Returns a const iterator to the first key-value pair with key that is _not less_ than the given key. 

**Return**: An iterator to the first matching key-value pair, or [end()](/libpalliate/generated/Classes/classtable#function-end). 

\availability This overload is only available when [TOML_ENABLE_WINDOWS_COMPAT](/libpalliate/generated/Files/toml_8hpp#define-toml-enable-windows-compat) is enabled.


### function find

```cpp
TOML_PURE_GETTERTOML_EXPORTED_MEMBER_FUNCTIONiterator find(
    std::string_view key
)
```

Gets an iterator to the node at a specific key. 

**Parameters**: 

  * **key** The node's key.


**Return**: An iterator to the node at the specified key, or [end()](/libpalliate/generated/Classes/classtable#function-end). 

### function find

```cpp
TOML_PURE_GETTERTOML_EXPORTED_MEMBER_FUNCTIONconst_iterator find(
    std::string_view key
) const
```

Gets an iterator to the node at a specific key (const overload) 

**Parameters**: 

  * **key** The node's key.


**Return**: A const iterator to the node at the specified key, or [cend()](/libpalliate/generated/Classes/classtable#function-cend). 

### function contains

```cpp
inline TOML_PURE_GETTER bool contains(
    std::string_view key
) const
```

Returns true if the table contains a node at the given key. 

### function find

```cpp
inline TOML_NODISCARDiterator find(
    std::wstring_view key
)
```

Gets an iterator to the node at a specific key. 

**Parameters**: 

  * **key** The node's key.


**Return**: An iterator to the node at the specified key, or [end()](/libpalliate/generated/Classes/classtable#function-end). 

\availability This overload is only available when [TOML_ENABLE_WINDOWS_COMPAT](/libpalliate/generated/Files/toml_8hpp#define-toml-enable-windows-compat) is enabled.


### function find

```cpp
inline TOML_NODISCARDconst_iterator find(
    std::wstring_view key
) const
```

Gets an iterator to the node at a specific key (const overload). 

**Parameters**: 

  * **key** The node's key.


**Return**: A const iterator to the node at the specified key, or [cend()](/libpalliate/generated/Classes/classtable#function-cend). 

\availability This overload is only available when [TOML_ENABLE_WINDOWS_COMPAT](/libpalliate/generated/Files/toml_8hpp#define-toml-enable-windows-compat) is enabled.


### function contains

```cpp
inline TOML_NODISCARD bool contains(
    std::wstring_view key
) const
```

Returns true if the table contains a node at the given key. 

\availability This overload is only available when [TOML_ENABLE_WINDOWS_COMPAT](/libpalliate/generated/Files/toml_8hpp#define-toml-enable-windows-compat) is enabled. 


### function erase

```cpp
inline iterator erase(
    iterator pos
)
```

Removes the specified key-value pair from the table. 

**Parameters**: 

  * **pos** Iterator to the key-value pair being erased.


**Return**: Iterator to the first key-value pair immediately following the removed key-value pair. 

\detail \cpp auto tbl = toml::table{ { "a", 1 }, { "b", 2 }, { "c", 3 } }; std::cout << tbl << "\n";

tbl.erase(tbl.begin() + 1); std::cout << tbl << "\n"; \ecpp

\out { a = 1, b = 2, c = 3 } { a = 1, c = 3 } \eout


### function erase

```cpp
inline iterator erase(
    const_iterator pos
)
```

Removes the specified key-value pair from the table (const iterator overload). 

**Parameters**: 

  * **pos** Iterator to the key-value pair being erased.


**Return**: Iterator to the first key-value pair immediately following the removed key-value pair. 

\detail \cpp auto tbl = toml::table{ { "a", 1 }, { "b", 2 }, { "c", 3 } }; std::cout << tbl << "\n";

tbl.erase(tbl.cbegin() + 1); std::cout << tbl << "\n"; \ecpp

\out { a = 1, b = 2, c = 3 } { a = 1, c = 3 } \eout


### function erase

```cpp
inline iterator erase(
    const_iterator begin,
    const_iterator end
)
```

Removes the key-value pairs in the range [first, last) from the table. 

**Parameters**: 

  * **begin** Iterator to the first key-value pair being erased. 
  * **end** Iterator to the one-past-the-last key-value pair being erased.


**Return**: Iterator to the first key-value pair immediately following the last removed key-value pair. 

\detail \cpp auto tbl = toml::table{ { "a", 1 }, { "b", "bad" }, { "c", "karma" }, { "d", 2 } }; std::cout << tbl << "\n";

tbl.erase(tbl.cbegin() + 1, tbl.cbegin() + 3); std::cout << tbl << "\n"; \ecpp

\out { a = 1, b = "bad", c = "karma", d = 2 } { a = 1, d = 2 } \eout


### function erase

```cpp
TOML_EXPORTED_MEMBER_FUNCTION size_t erase(
    std::string_view key
)
```

Removes the value with the given key from the table. 

**Parameters**: 

  * **key** Key to erase.


**Return**: Number of elements removed (0 or 1). 

\detail \cpp auto tbl = toml::table{ { "a", 1 }, { "b", 2 }, { "c", 3 } }; std::cout << tbl << "\n";

std::cout << tbl.erase("b") << "\n"; std::cout << tbl.erase("not an existing key") << "\n"; std::cout << tbl << "\n"; \ecpp

\out { a = 1, b = 2, c = 3 } true false { a = 1, c = 3 } \eout


### function erase

```cpp
inline size_t erase(
    std::wstring_view key
)
```

Removes the value with the given key from the table. 

**Parameters**: 

  * **key** Key to erase.


**Return**: Number of elements removed (0 or 1). 

\availability This overload is only available when [TOML_ENABLE_WINDOWS_COMPAT](/libpalliate/generated/Files/toml_8hpp#define-toml-enable-windows-compat) is enabled.


### function prune

```cpp
TOML_EXPORTED_MEMBER_FUNCTIONtable & prune(
    bool recursive =true
)
```

Removes empty child arrays and tables. 

**Parameters**: 

  * **recursive** Should child arrays and tables themselves be pruned?


**Return**: A reference to the table. 

\detail \cpp

auto tbl = toml::table{ { "a", 1 }, { "b", toml::array{ } }, { "c", toml::array{ toml::table{}, toml::array{} } } }; std::cout << arr << "\n";

arr.prune(); std::cout << arr << "\n"; \ecpp

\out { a = 1, b = [], c = [ {}, [] ] } { a = 1 } \eout


### function prune

```cpp
inline table && prune(
    bool recursive =true
)
```

Removes empty child arrays and tables (rvalue overload). 

**Parameters**: 

  * **recursive** Should child arrays and tables themselves be pruned?


**Return**: An rvalue reference to the table. 

### function clear

```cpp
TOML_EXPORTED_MEMBER_FUNCTION void clear()
```

Removes all key-value pairs from the table. 

### function TOML_CONSTRAINED_TEMPLATE

```cpp
TOML_CONSTRAINED_TEMPLATE(
    (is_key_or_convertible< KeyType && >||impl::is_wide_string< KeyType >) ,
    typename ValueType ,
    typename KeyType ,
    typename... ValueArgs
)
```

Emplaces a new value at a specific key if one did not already exist. 

**Parameters**: 

  * **hint** Iterator to the position before which the new element will be emplaced. 
  * **key** The key at which to emplace the new value. 
  * **args** Arguments to forward to the value's constructor.


**Template Parameters**: 

  * **ValueType** toml::table, toml::array, or any native TOML value type. 
  * **KeyType** A toml::key or any compatible string type. 
  * **ValueArgs** Value constructor argument types. 


**Return**: An iterator to the emplacement position (or the position of the value that prevented emplacement)

**Note**: This function has exactly the same semantics as [std::map::emplace_hint()](https://en.cppreference.com/w/cpp/container/map/emplace_hint). 

### function if

```cpp
inline constexpr if(
    impl::is_wide_string< KeyType > 
)
```


### function if

```cpp
inline if(
    !ipos-> second
)
```


### function TOML_CONSTRAINED_TEMPLATE

```cpp
inline TOML_CONSTRAINED_TEMPLATE(
    (is_key_or_convertible< KeyType && >||impl::is_wide_string< KeyType >) ,
    typename KeyType ,
    typename ValueType 
)
```

Inserts a new value at a specific key if one did not already exist. 

**Parameters**: 

  * **key** The key at which to insert the new value. 
  * **val** The new value to insert. 
  * **flags** Value flags to apply to new values.


**Template Parameters**: 

  * **KeyType** A toml::key or any compatible string type. 
  * **ValueType** toml::node, toml::node_view, toml::table, toml::array, or a native TOML value type (or a type promotable to one). 


**Return**: \conditional_return{Valid input} 

* An iterator to the insertion position (or the position of the value that prevented insertion) 
* A boolean indicating if the insertion was successful. 

\conditional_return{Input is a null toml::node_view} `{ [end()](/libpalliate/generated/Classes/classtable#function-end), false }`

**Attention**: The return value will always be `{ [end()](/libpalliate/generated/Classes/classtable#function-end), false }` if the input value was an null toml::node_view, because no insertion can take place. This is the only circumstance in which this can occur. 

\detail \godbolt{bMnW5r}

\cpp auto tbl = toml::table{ { "a", 1 }, { "b", 2 }, { "c", 3 } }; std::cout << tbl << "\n";

for (auto k : { "a", "d" }) { auto result = tbl.insert(k, 42); std::cout << "inserted with key '"sv << k << "': "sv << result.second << "\n"; } std::cout << tbl << "\n"; \ecpp

\out a = 1 b = 2 c = 3

inserted with key 'a': false inserted with key 'd': true a = 1 b = 2 c = 3 d = 42 \eout


### function insert

```cpp
inline void insert(
    Iter begin,
    Iter end,
    value_flags flags =preserve_source_value_flags
)
```

Inserts a series of key-value pairs into the table. 

**Parameters**: 

  * **begin** An iterator to the first value in the input collection. 
  * **end** An iterator to one-past-the-last value in the input collection. 
  * **flags** Value flags to apply to new values.


**Template Parameters**: 

  * **Iter** An InputIterator to a collection of key-value pairs. 


**Remark**: This function is morally equivalent to calling `insert(key, value)` for each key-value pair covered by the iterator range, so any values with keys already found in the table will not be replaced. 

\detail \godbolt{bzYcce}

\cpp auto tbl = toml::table{ { "a", 1 }, { "b", 2 }, { "c", 3 } }; std::cout << tbl << "\n";

auto kvps = std::array<std::pair<std::string, int>, 2>{{ { "d", 42 }, { "a", 43 } // won't be inserted, 'a' already exists }}; tbl.insert(kvps.begin(), kvps.end()); std::cout << tbl << "\n"; \ecpp

\out a = 1 b = 2 c = 3

a = 1 b = 2 c = 3 d = 42 \eout


### function TOML_CONSTRAINED_TEMPLATE

```cpp
inline TOML_CONSTRAINED_TEMPLATE(
    (is_key_or_convertible< KeyType && >||impl::is_wide_string< KeyType >) ,
    typename KeyType ,
    typename ValueType 
)
```

Inserts or assigns a value at a specific key. 

**Parameters**: 

  * **key** The key at which to insert the new value. 
  * **val** The new value to insert. 
  * **flags** Value flags to apply to new values.


**Template Parameters**: 

  * **KeyType** A toml::key or any compatible string type. 
  * **ValueType** toml::node, toml::node_view, toml::table, toml::array, or a native TOML value type (or a type promotable to one). 


**Return**: \conditional_return{Valid input} 

* An iterator to the insertion position (or the position of the value that prevented insertion) 
* A boolean indicating if the insertion was successful. 

\conditional_return{Input is a null toml::node_view} `{ [end()](/libpalliate/generated/Classes/classtable#function-end), false }`

**Attention**: The return value will always be `{ [end()](/libpalliate/generated/Classes/classtable#function-end), false }` if the input value was an null toml::node_view, because no insertion can take place. This is the only circumstance in which this can occur. 

\detail \godbolt{bMnW5r}

\cpp auto tbl = toml::table{ { "a", 1 }, { "b", 2 }, { "c", 3 } }; std::cout << tbl << "\n";

for (auto k : { "a", "d" }) { auto result = tbl.insert(k, 42); std::cout << "inserted with key '"sv << k << "': "sv << result.second << "\n"; } std::cout << tbl << "\n"; \ecpp

\out a = 1 b = 2 c = 3

inserted with key 'a': false inserted with key 'd': true a = 1 b = 2 c = 3 d = 42 \eout


### function TOML_CONSTRAINED_TEMPLATE

```cpp
inline TOML_CONSTRAINED_TEMPLATE(
    (is_key_or_convertible< KeyType && >||impl::is_wide_string< KeyType >) ,
    typename ValueType ,
    typename KeyType ,
    typename... ValueArgs
)
```

Emplaces a new value at a specific key if one did not already exist. 

**Parameters**: 

  * **key** The key at which to emplace the new value. 
  * **args** Arguments to forward to the value's constructor.


**Template Parameters**: 

  * **ValueType** toml::table, toml::array, or any native TOML value type. 
  * **KeyType** A toml::key or any compatible string type. 
  * **ValueArgs** Value constructor argument types. 


**Return**: A std::pair containing: 


* An iterator to the emplacement position (or the position of the value that prevented emplacement)
* A boolean indicating if the emplacement was successful.

**Remark**: There is no difference between [insert()](/libpalliate/generated/Classes/classtable#function-insert) and emplace() for trivial value types (floats, ints, bools). 

\detail \cpp auto tbl = toml::table{ { "a", 1 }, { "b", 2 }, { "c", 3 } }; std::cout << tbl << "\n";

for (auto k : { "a", "d" }) { // add a string using std::string's substring constructor auto result = tbl.emplace<std::string>(k, "this is not a drill"sv, 14, 5); std::cout << "emplaced with key '"sv << k << "': "sv << result.second << "\n"; } std::cout << tbl << "\n"; \ecpp

\out { a = 1, b = 2, c = 3 } emplaced with key 'a': false emplaced with key 'd': true { a = 1, b = 2, c = 3, d = "drill" } \eout


### function operator[]

```cpp
inline TOML_NODISCARDnode_view< node > operator[](
    std::string_view key
)
```

Gets a [node_view]() for the selected value. 

**Parameters**: 

  * **key** The key used for the lookup.


**See**: toml::node_view 

**Return**: A view of the value at the given key if one existed, or an empty node view.

**Remark**: std::map::operator[]'s behaviour of default-constructing a value at a key if it didn't exist is a crazy bug factory so I've deliberately chosen not to emulate it. **This is not an error.**

### function operator[]

```cpp
inline TOML_NODISCARDnode_view< const node > operator[](
    std::string_view key
) const
```

Gets a [node_view]() for the selected value (const overload). 

**Parameters**: 

  * **key** The key used for the lookup.


**See**: toml::node_view 

**Return**: A view of the value at the given key if one existed, or an empty node view.

**Remark**: std::map::operator[]'s behaviour of default-constructing a value at a key if it didn't exist is a crazy bug factory so I've deliberately chosen not to emulate it. **This is not an error.**

### function operator[]

```cpp
inline TOML_NODISCARDnode_view< node > operator[](
    std::wstring_view key
)
```

Gets a [node_view]() for the selected value. 

**Parameters**: 

  * **key** The key used for the lookup.


**See**: toml::node_view 

**Return**: A view of the value at the given key if one existed, or an empty node view.

**Remark**: std::map::operator[]'s behaviour of default-constructing a value at a key if it didn't exist is a crazy bug factory so I've deliberately chosen not to emulate it. **This is not an error.**

\availability This overload is only available when [TOML_ENABLE_WINDOWS_COMPAT](/libpalliate/generated/Files/toml_8hpp#define-toml-enable-windows-compat) is enabled.


### function operator[]

```cpp
inline TOML_NODISCARDnode_view< const node > operator[](
    std::wstring_view key
) const
```

Gets a [node_view]() for the selected value (const overload). 

**Parameters**: 

  * **key** The key used for the lookup.


**See**: toml::node_view 

**Return**: A view of the value at the given key if one existed, or an empty node view.

**Remark**: std::map::operator[]'s behaviour of default-constructing a value at a key if it didn't exist is a crazy bug factory so I've deliberately chosen not to emulate it. **This is not an error.**

\availability This overload is only available when [TOML_ENABLE_WINDOWS_COMPAT](/libpalliate/generated/Files/toml_8hpp#define-toml-enable-windows-compat) is enabled.


### function table

```cpp
TOML_NODISCARD_CTORTOML_EXPORTED_MEMBER_FUNCTION table()
```

Default constructor. 

### function ~table

```cpp
TOML_EXPORTED_MEMBER_FUNCTION ~table()
```


### function table

```cpp
TOML_NODISCARD_CTORTOML_EXPORTED_MEMBER_FUNCTION table(
    const table & 
)
```

Copy constructor. 

### function table

```cpp
TOML_NODISCARD_CTORTOML_EXPORTED_MEMBER_FUNCTION table(
    table && other
)
```

Move constructor. 

### function table

```cpp
inline explicit TOML_NODISCARD_CTORTOML_EXPORTED_MEMBER_FUNCTION table(
    std::initializer_list< impl::table_init_pair > kvps
)
```

Constructs a table with one or more initial key-value pairs. 

**Parameters**: 

  * **kvps** A list of key-value pairs used to initialize the table. 


\detail \cpp auto tbl = toml::table{ { "foo", 1 }, { "bar", 2.0 }, { "kek", "three" } }; std::cout << tbl << "\n"; \ecpp

\out { foo = 1, bar = 2.0, kek = "three" } \eout


### function operator=

```cpp
TOML_EXPORTED_MEMBER_FUNCTIONtable & operator=(
    const table & 
)
```

Copy-assignment operator. 

### function operator=

```cpp
TOML_EXPORTED_MEMBER_FUNCTIONtable & operator=(
    table && rhs
)
```

Move-assignment operator. 

### function table

```cpp
TOML_NODISCARD_CTORTOML_EXPORTED_MEMBER_FUNCTION table()
```


### function ~table

```cpp
TOML_EXPORTED_MEMBER_FUNCTION ~table()
```


### function table

```cpp
TOML_NODISCARD_CTORTOML_EXPORTED_MEMBER_FUNCTION table(
    const table & 
)
```


### function table

```cpp
TOML_NODISCARD_CTORTOML_EXPORTED_MEMBER_FUNCTION table(
    table && other
)
```


### function table

```cpp
inline explicit TOML_NODISCARD_CTORTOML_EXPORTED_MEMBER_FUNCTION table(
    std::initializer_list< impl::table_init_pair > kvps
)
```


**Parameters**: 

  * **kvps** A list of key-value pairs used to initialize the table. 


\detail \cpp auto tbl = toml::table{ { "foo", 1 }, { "bar", 2.0 }, { "kek", "three" } }; std::cout << tbl << "\n"; \ecpp

\out { foo = 1, bar = 2.0, kek = "three" } \eout


### function operator=

```cpp
TOML_EXPORTED_MEMBER_FUNCTIONtable & operator=(
    const table & 
)
```


### function operator=

```cpp
TOML_EXPORTED_MEMBER_FUNCTIONtable & operator=(
    table && rhs
)
```


### function type

```cpp
inline TOML_CONST_INLINE_GETTER node_type type() const
```


### function is_homogeneous

```cpp
TOML_PURE_GETTERTOML_EXPORTED_MEMBER_FUNCTION bool is_homogeneous(
    node_type ntype
) const
```


### function is_homogeneous

```cpp
TOML_PURE_GETTERTOML_EXPORTED_MEMBER_FUNCTION bool is_homogeneous(
    node_type ntype,
    node *& first_nonmatch
)
```


### function is_homogeneous

```cpp
TOML_PURE_GETTERTOML_EXPORTED_MEMBER_FUNCTION bool is_homogeneous(
    node_type ntype,
    const node *& first_nonmatch
) const
```


### function is_homogeneous

```cpp
template <typename ElemType  =void>
inline TOML_PURE_GETTER bool is_homogeneous() const
```


### function is_table

```cpp
inline TOML_CONST_INLINE_GETTER bool is_table() const
```


### function is_array

```cpp
inline TOML_CONST_INLINE_GETTER bool is_array() const
```


### function is_array_of_tables

```cpp
inline TOML_PURE_GETTER bool is_array_of_tables() const
```


### function is_value

```cpp
inline TOML_CONST_INLINE_GETTER bool is_value() const
```


### function is_string

```cpp
inline TOML_CONST_INLINE_GETTER bool is_string() const
```


### function is_integer

```cpp
inline TOML_CONST_INLINE_GETTER bool is_integer() const
```


### function is_floating_point

```cpp
inline TOML_CONST_INLINE_GETTER bool is_floating_point() const
```


### function is_number

```cpp
inline TOML_CONST_INLINE_GETTER bool is_number() const
```


### function is_boolean

```cpp
inline TOML_CONST_INLINE_GETTER bool is_boolean() const
```


### function is_date

```cpp
inline TOML_CONST_INLINE_GETTER bool is_date() const
```


### function is_time

```cpp
inline TOML_CONST_INLINE_GETTER bool is_time() const
```


### function is_date_time

```cpp
inline TOML_CONST_INLINE_GETTER bool is_date_time() const
```


### function as_table

```cpp
inline TOML_CONST_INLINE_GETTERtable * as_table()
```


### function as_array

```cpp
inline TOML_CONST_INLINE_GETTERarray * as_array()
```


### function as_string

```cpp
inline TOML_CONST_INLINE_GETTERtoml::value< std::string > * as_string()
```


### function as_integer

```cpp
inline TOML_CONST_INLINE_GETTERtoml::value< int64_t > * as_integer()
```


### function as_floating_point

```cpp
inline TOML_CONST_INLINE_GETTERtoml::value< double > * as_floating_point()
```


### function as_boolean

```cpp
inline TOML_CONST_INLINE_GETTERtoml::value< bool > * as_boolean()
```


### function as_date

```cpp
inline TOML_CONST_INLINE_GETTERtoml::value< date > * as_date()
```


### function as_time

```cpp
inline TOML_CONST_INLINE_GETTERtoml::value< time > * as_time()
```


### function as_date_time

```cpp
inline TOML_CONST_INLINE_GETTERtoml::value< date_time > * as_date_time()
```


### function as_table

```cpp
inline const TOML_CONST_INLINE_GETTERtable * as_table() const
```


### function as_array

```cpp
inline const TOML_CONST_INLINE_GETTERarray * as_array() const
```


### function as_string

```cpp
inline const TOML_CONST_INLINE_GETTERtoml::value< std::string > * as_string() const
```


### function as_integer

```cpp
inline const TOML_CONST_INLINE_GETTERtoml::value< int64_t > * as_integer() const
```


### function as_floating_point

```cpp
inline const TOML_CONST_INLINE_GETTERtoml::value< double > * as_floating_point() const
```


### function as_boolean

```cpp
inline const TOML_CONST_INLINE_GETTERtoml::value< bool > * as_boolean() const
```


### function as_date

```cpp
inline const TOML_CONST_INLINE_GETTERtoml::value< date > * as_date() const
```


### function as_time

```cpp
inline const TOML_CONST_INLINE_GETTERtoml::value< time > * as_time() const
```


### function as_date_time

```cpp
inline const TOML_CONST_INLINE_GETTERtoml::value< date_time > * as_date_time() const
```


### function is_inline

```cpp
inline TOML_PURE_INLINE_GETTER bool is_inline() const
```


**Remark**: Runtime-constructed tables (i.e. those not created during parsing) are not inline by default. 

### function is_inline

```cpp
inline void is_inline(
    bool val
)
```


**Parameters**: 

  * **val** The new value for 'inline'. 


**Remark**: A table being 'inline' is only relevent during printing; it has no effect on the general functionality of the table object.

\detail \godbolt{an9xdj}

\cpp auto tbl = toml::table{ { "a", 1 }, { "b", 2 }, { "c", 3 }, { "d", toml::table{ { "e", 4 } } } }; std::cout << "is inline? "sv << tbl.is_inline() << "\n"; std::cout << tbl << "\n\n";

tbl.is_inline(!tbl.[is_inline()](/libpalliate/generated/Classes/classtable#function-is-inline)); std::cout << "is inline? "sv << tbl.is_inline() << "\n"; std::cout << tbl << "\n"; \ecpp

\out is inline? false a = 1 b = 2 c = 3

[d] e = 4

is inline? true { a = 1, b = 2, c = 3, d = { e = 4 } } \eout


### function get

```cpp
TOML_PURE_GETTERTOML_EXPORTED_MEMBER_FUNCTION node * get(
    std::string_view key
)
```


**Parameters**: 

  * **key** The node's key.


**Return**: A pointer to the node at the specified key, or nullptr. 

\detail \cpp auto tbl = toml::table{ { "a", 42, }, { "b", "is the meaning of life, apparently." } }; std::cout << R"(node ["a"] exists: )"sv << !!arr.get("a") << "\n"; std::cout << R"(node ["b"] exists: )"sv << !!arr.get("b") << "\n"; std::cout << R"(node ["c"] exists: )"sv << !!arr.get("c") << "\n"; if (auto val = arr.get("a")) std::cout << R"(node ["a"] was an )"sv << val->[type()](/libpalliate/generated/Classes/classtable#function-type) << "\n"; \ecpp

\out node ["a"] exists: true node ["b"] exists: true node ["c"] exists: false node ["a"] was an integer \eout


### function get

```cpp
inline const TOML_PURE_INLINE_GETTER node * get(
    std::string_view key
) const
```


**Parameters**: 

  * **key** The node's key.


**Return**: A pointer to the node at the specified key, or nullptr. 

### function get_as

```cpp
template <typename T >
inline TOML_PURE_GETTERimpl::wrap_node< T > * get_as(
    std::string_view key
)
```


**Parameters**: 

  * **key** The node's key.


**Template Parameters**: 

  * **T** One of the TOML node or value types. 


**Return**: A pointer to the node at the specified key if it was of the given type, or nullptr. 

\detail \cpp auto tbl = toml::table{ { "a", 42, }, { "b", "is the meaning of life, apparently." } }; if (auto val = arr.get_as<int64_t>("a")) std::cout << R"(node ["a"] was an integer with value )"sv << **val << "\n"; \ecpp

\out node ["a"] was an integer with value 42 \eout


### function get_as

```cpp
template <typename T >
inline const TOML_PURE_GETTERimpl::wrap_node< T > * get_as(
    std::string_view key
) const
```


**Parameters**: 

  * **key** The node's key.


**Template Parameters**: 

  * **T** One of the TOML node or value types. 


**Return**: A pointer to the node at the specified key if it was of the given type, or nullptr. 

### function at

```cpp
TOML_NODISCARDTOML_EXPORTED_MEMBER_FUNCTION node & at(
    std::string_view key
)
```


### function at

```cpp
inline const TOML_NODISCARD node & at(
    std::string_view key
) const
```


### function begin

```cpp
inline TOML_PURE_INLINE_GETTERiterator begin()
```


### function begin

```cpp
inline TOML_PURE_INLINE_GETTERconst_iterator begin() const
```


### function cbegin

```cpp
inline TOML_PURE_INLINE_GETTERconst_iterator cbegin() const
```


### function end

```cpp
inline TOML_PURE_INLINE_GETTERiterator end()
```


### function end

```cpp
inline TOML_PURE_INLINE_GETTERconst_iterator end() const
```


### function cend

```cpp
inline TOML_PURE_INLINE_GETTERconst_iterator cend() const
```


### function empty

```cpp
inline TOML_PURE_INLINE_GETTER bool empty() const
```


### function size

```cpp
inline TOML_PURE_INLINE_GETTER size_t size() const
```


### function lower_bound

```cpp
inline TOML_PURE_GETTERiterator lower_bound(
    std::string_view key
)
```


**Return**: An iterator to the first matching key-value pair, or [end()](/libpalliate/generated/Classes/classtable#function-end). 

### function lower_bound

```cpp
inline TOML_PURE_GETTERconst_iterator lower_bound(
    std::string_view key
) const
```


**Return**: An iterator to the first matching key-value pair, or [end()](/libpalliate/generated/Classes/classtable#function-end). 

### function find

```cpp
TOML_PURE_GETTERTOML_EXPORTED_MEMBER_FUNCTIONiterator find(
    std::string_view key
)
```


**Parameters**: 

  * **key** The node's key.


**Return**: An iterator to the node at the specified key, or [end()](/libpalliate/generated/Classes/classtable#function-end). 

### function find

```cpp
TOML_PURE_GETTERTOML_EXPORTED_MEMBER_FUNCTIONconst_iterator find(
    std::string_view key
) const
```


**Parameters**: 

  * **key** The node's key.


**Return**: A const iterator to the node at the specified key, or [cend()](/libpalliate/generated/Classes/classtable#function-cend). 

### function contains

```cpp
inline TOML_PURE_GETTER bool contains(
    std::string_view key
) const
```


### function erase

```cpp
inline iterator erase(
    iterator pos
)
```


**Parameters**: 

  * **pos** Iterator to the key-value pair being erased.


**Return**: Iterator to the first key-value pair immediately following the removed key-value pair. 

\detail \cpp auto tbl = toml::table{ { "a", 1 }, { "b", 2 }, { "c", 3 } }; std::cout << tbl << "\n";

tbl.erase(tbl.begin() + 1); std::cout << tbl << "\n"; \ecpp

\out { a = 1, b = 2, c = 3 } { a = 1, c = 3 } \eout


### function erase

```cpp
inline iterator erase(
    const_iterator pos
)
```


**Parameters**: 

  * **pos** Iterator to the key-value pair being erased.


**Return**: Iterator to the first key-value pair immediately following the removed key-value pair. 

\detail \cpp auto tbl = toml::table{ { "a", 1 }, { "b", 2 }, { "c", 3 } }; std::cout << tbl << "\n";

tbl.erase(tbl.cbegin() + 1); std::cout << tbl << "\n"; \ecpp

\out { a = 1, b = 2, c = 3 } { a = 1, c = 3 } \eout


### function erase

```cpp
inline iterator erase(
    const_iterator begin,
    const_iterator end
)
```


**Parameters**: 

  * **begin** Iterator to the first key-value pair being erased. 
  * **end** Iterator to the one-past-the-last key-value pair being erased.


**Return**: Iterator to the first key-value pair immediately following the last removed key-value pair. 

\detail \cpp auto tbl = toml::table{ { "a", 1 }, { "b", "bad" }, { "c", "karma" }, { "d", 2 } }; std::cout << tbl << "\n";

tbl.erase(tbl.cbegin() + 1, tbl.cbegin() + 3); std::cout << tbl << "\n"; \ecpp

\out { a = 1, b = "bad", c = "karma", d = 2 } { a = 1, d = 2 } \eout


### function erase

```cpp
TOML_EXPORTED_MEMBER_FUNCTION size_t erase(
    std::string_view key
)
```


**Parameters**: 

  * **key** Key to erase.


**Return**: Number of elements removed (0 or 1). 

\detail \cpp auto tbl = toml::table{ { "a", 1 }, { "b", 2 }, { "c", 3 } }; std::cout << tbl << "\n";

std::cout << tbl.erase("b") << "\n"; std::cout << tbl.erase("not an existing key") << "\n"; std::cout << tbl << "\n"; \ecpp

\out { a = 1, b = 2, c = 3 } true false { a = 1, c = 3 } \eout


### function prune

```cpp
TOML_EXPORTED_MEMBER_FUNCTIONtable & prune(
    bool recursive =true
)
```


**Parameters**: 

  * **recursive** Should child arrays and tables themselves be pruned?


**Return**: A reference to the table. 

\detail \cpp

auto tbl = toml::table{ { "a", 1 }, { "b", toml::array{ } }, { "c", toml::array{ toml::table{}, toml::array{} } } }; std::cout << arr << "\n";

arr.prune(); std::cout << arr << "\n"; \ecpp

\out { a = 1, b = [], c = [ {}, [] ] } { a = 1 } \eout


### function prune

```cpp
inline table && prune(
    bool recursive =true
)
```


**Parameters**: 

  * **recursive** Should child arrays and tables themselves be pruned?


**Return**: An rvalue reference to the table. 

### function clear

```cpp
TOML_EXPORTED_MEMBER_FUNCTION void clear()
```


### function TOML_CONSTRAINED_TEMPLATE

```cpp
TOML_CONSTRAINED_TEMPLATE(
    (is_key_or_convertible< KeyType && >||impl::is_wide_string< KeyType >) ,
    typename ValueType ,
    typename KeyType ,
    typename... ValueArgs
)
```


**Parameters**: 

  * **hint** Iterator to the position before which the new element will be emplaced. 
  * **key** The key at which to emplace the new value. 
  * **args** Arguments to forward to the value's constructor.


**Template Parameters**: 

  * **ValueType** toml::table, toml::array, or any native TOML value type. 
  * **KeyType** A toml::key or any compatible string type. 
  * **ValueArgs** Value constructor argument types. 


**Return**: An iterator to the emplacement position (or the position of the value that prevented emplacement)

**Note**: This function has exactly the same semantics as [std::map::emplace_hint()](https://en.cppreference.com/w/cpp/container/map/emplace_hint). 

### function if

```cpp
inline constexpr if(
    impl::is_wide_string< KeyType > 
)
```


### function if

```cpp
inline if(
    !ipos-> second
)
```


### function TOML_CONSTRAINED_TEMPLATE

```cpp
inline TOML_CONSTRAINED_TEMPLATE(
    (is_key_or_convertible< KeyType && >||impl::is_wide_string< KeyType >) ,
    typename KeyType ,
    typename ValueType 
)
```


**Parameters**: 

  * **key** The key at which to insert the new value. 
  * **val** The new value to insert. 
  * **flags** Value flags to apply to new values.


**Template Parameters**: 

  * **KeyType** A toml::key or any compatible string type. 
  * **ValueType** toml::node, toml::node_view, toml::table, toml::array, or a native TOML value type (or a type promotable to one). 


**Return**: \conditional_return{Valid input} 

* An iterator to the insertion position (or the position of the value that prevented insertion) 
* A boolean indicating if the insertion was successful. 

\conditional_return{Input is a null toml::node_view} `{ [end()](/libpalliate/generated/Classes/classtable#function-end), false }`

**Attention**: The return value will always be `{ [end()](/libpalliate/generated/Classes/classtable#function-end), false }` if the input value was an null toml::node_view, because no insertion can take place. This is the only circumstance in which this can occur. 

\detail \godbolt{bMnW5r}

\cpp auto tbl = toml::table{ { "a", 1 }, { "b", 2 }, { "c", 3 } }; std::cout << tbl << "\n";

for (auto k : { "a", "d" }) { auto result = tbl.insert(k, 42); std::cout << "inserted with key '"sv << k << "': "sv << result.second << "\n"; } std::cout << tbl << "\n"; \ecpp

\out a = 1 b = 2 c = 3

inserted with key 'a': false inserted with key 'd': true a = 1 b = 2 c = 3 d = 42 \eout


### function insert

```cpp
inline void insert(
    Iter begin,
    Iter end,
    value_flags flags =preserve_source_value_flags
)
```


**Parameters**: 

  * **begin** An iterator to the first value in the input collection. 
  * **end** An iterator to one-past-the-last value in the input collection. 
  * **flags** Value flags to apply to new values.


**Template Parameters**: 

  * **Iter** An InputIterator to a collection of key-value pairs. 


**Remark**: This function is morally equivalent to calling `insert(key, value)` for each key-value pair covered by the iterator range, so any values with keys already found in the table will not be replaced. 

\detail \godbolt{bzYcce}

\cpp auto tbl = toml::table{ { "a", 1 }, { "b", 2 }, { "c", 3 } }; std::cout << tbl << "\n";

auto kvps = std::array<std::pair<std::string, int>, 2>{{ { "d", 42 }, { "a", 43 } // won't be inserted, 'a' already exists }}; tbl.insert(kvps.begin(), kvps.end()); std::cout << tbl << "\n"; \ecpp

\out a = 1 b = 2 c = 3

a = 1 b = 2 c = 3 d = 42 \eout


### function TOML_CONSTRAINED_TEMPLATE

```cpp
inline TOML_CONSTRAINED_TEMPLATE(
    (is_key_or_convertible< KeyType && >||impl::is_wide_string< KeyType >) ,
    typename KeyType ,
    typename ValueType 
)
```


**Parameters**: 

  * **key** The key at which to insert the new value. 
  * **val** The new value to insert. 
  * **flags** Value flags to apply to new values.


**Template Parameters**: 

  * **KeyType** A toml::key or any compatible string type. 
  * **ValueType** toml::node, toml::node_view, toml::table, toml::array, or a native TOML value type (or a type promotable to one). 


**Return**: \conditional_return{Valid input} 

* An iterator to the insertion position (or the position of the value that prevented insertion) 
* A boolean indicating if the insertion was successful. 

\conditional_return{Input is a null toml::node_view} `{ [end()](/libpalliate/generated/Classes/classtable#function-end), false }`

**Attention**: The return value will always be `{ [end()](/libpalliate/generated/Classes/classtable#function-end), false }` if the input value was an null toml::node_view, because no insertion can take place. This is the only circumstance in which this can occur. 

\detail \godbolt{bMnW5r}

\cpp auto tbl = toml::table{ { "a", 1 }, { "b", 2 }, { "c", 3 } }; std::cout << tbl << "\n";

for (auto k : { "a", "d" }) { auto result = tbl.insert(k, 42); std::cout << "inserted with key '"sv << k << "': "sv << result.second << "\n"; } std::cout << tbl << "\n"; \ecpp

\out a = 1 b = 2 c = 3

inserted with key 'a': false inserted with key 'd': true a = 1 b = 2 c = 3 d = 42 \eout


### function TOML_CONSTRAINED_TEMPLATE

```cpp
inline TOML_CONSTRAINED_TEMPLATE(
    (is_key_or_convertible< KeyType && >||impl::is_wide_string< KeyType >) ,
    typename ValueType ,
    typename KeyType ,
    typename... ValueArgs
)
```


**Parameters**: 

  * **key** The key at which to emplace the new value. 
  * **args** Arguments to forward to the value's constructor.


**Template Parameters**: 

  * **ValueType** toml::table, toml::array, or any native TOML value type. 
  * **KeyType** A toml::key or any compatible string type. 
  * **ValueArgs** Value constructor argument types. 


**Return**: A std::pair containing: 


* An iterator to the emplacement position (or the position of the value that prevented emplacement)
* A boolean indicating if the emplacement was successful.

**Remark**: There is no difference between [insert()](/libpalliate/generated/Classes/classtable#function-insert) and emplace() for trivial value types (floats, ints, bools). 

\detail \cpp auto tbl = toml::table{ { "a", 1 }, { "b", 2 }, { "c", 3 } }; std::cout << tbl << "\n";

for (auto k : { "a", "d" }) { // add a string using std::string's substring constructor auto result = tbl.emplace<std::string>(k, "this is not a drill"sv, 14, 5); std::cout << "emplaced with key '"sv << k << "': "sv << result.second << "\n"; } std::cout << tbl << "\n"; \ecpp

\out { a = 1, b = 2, c = 3 } emplaced with key 'a': false emplaced with key 'd': true { a = 1, b = 2, c = 3, d = "drill" } \eout


### function operator[]

```cpp
inline TOML_NODISCARDnode_view< node > operator[](
    std::string_view key
)
```


**Parameters**: 

  * **key** The key used for the lookup.


**See**: toml::node_view 

**Return**: A view of the value at the given key if one existed, or an empty node view.

**Remark**: std::map::operator[]'s behaviour of default-constructing a value at a key if it didn't exist is a crazy bug factory so I've deliberately chosen not to emulate it. **This is not an error.**

### function operator[]

```cpp
inline TOML_NODISCARDnode_view< const node > operator[](
    std::string_view key
) const
```


**Parameters**: 

  * **key** The key used for the lookup.


**See**: toml::node_view 

**Return**: A view of the value at the given key if one existed, or an empty node view.

**Remark**: std::map::operator[]'s behaviour of default-constructing a value at a key if it didn't exist is a crazy bug factory so I've deliberately chosen not to emulate it. **This is not an error.**

## Public Attributes Documentation

### variable key

```cpp
KeyType && key;
```


### variable args

```cpp
KeyType ValueArgs && args {
			static_assert(!impl::is_wide_string<KeyType> || TOML_ENABLE_WINDOWS_COMPAT,
						  "Emplacement using wide-character keys is only supported on Windows with "
						  "TOML_ENABLE_WINDOWS_COMPAT enabled.");
```


### variable else

```cpp
else {
				static constexpr auto moving_node_ptr = std::is_same_v<ValueType, impl::node_ptr> 
													 && sizeof...(ValueArgs) == 1u				  
													 && impl::first_is_same<impl::node_ptr&&, ValueArgs&&...>;
```


### variable ipos

```cpp
map_iterator ipos = insert_with_hint(hint, toml::key{ static_cast<KeyType&&>(key) }, nullptr);
```


### variable iterator

```cpp
toml::table_iterator iterator { ipos };
```


## Friends

### friend operator==

```cpp
friend TOML_NODISCARD friend bool operator==(
    const table & lhs,

    const table & rhs
);
```

Equality operator. 

**Parameters**: 

  * **lhs** The LHS table. 
  * **rhs** The RHS table.


**Return**: True if the tables contained the same keys and map. 

### friend operator!=

```cpp
friend TOML_NODISCARD friend bool operator!=(
    const table & lhs,

    const table & rhs
);
```

Inequality operator. 

**Parameters**: 

  * **lhs** The LHS table. 
  * **rhs** The RHS table.


**Return**: True if the tables did not contain the same keys and map. 

### friend operator<<

```cpp
friend std::ostream & operator<<(
    std::ostream & lhs,

    const table & rhs
);
```

Prints the table out to a stream as formatted TOML. 

\availability This operator is only available when [TOML_ENABLE_FORMATTERS](/libpalliate/generated/Files/toml_8hpp#define-toml-enable-formatters) is enabled. 


### friend operator==

```cpp
friend TOML_NODISCARD friend bool operator==(
    const table & lhs,

    const table & rhs
);
```


**Parameters**: 

  * **lhs** The LHS table. 
  * **rhs** The RHS table.


**Return**: True if the tables contained the same keys and map. 

### friend operator!=

```cpp
friend TOML_NODISCARD friend bool operator!=(
    const table & lhs,

    const table & rhs
);
```


**Parameters**: 

  * **lhs** The LHS table. 
  * **rhs** The RHS table.


**Return**: True if the tables did not contain the same keys and map. 

### friend operator<<

```cpp
friend std::ostream & operator<<(
    std::ostream & lhs,

    const table & rhs
);
```


\availability This operator is only available when [TOML_ENABLE_FORMATTERS](/libpalliate/generated/Files/toml_8hpp#define-toml-enable-formatters) is enabled. 



_Automatically updated on 2022-05-02 at 01:42:07 +0000._