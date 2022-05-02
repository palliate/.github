---
title: array
summary: A TOML array. 
parent: Classes
grand_parent: libpalliate
layout: default
---

# array



A TOML array.  [More...](#detailed-description)


`#include <toml.hpp>`

Inherits from node

## Public Types

|                | Name           |
| -------------- | -------------- |
| using array_iterator | **[iterator](/libpalliate/generated/Classes/classarray#using-iterator)** <br>A RandomAccessIterator for iterating over elements in a toml::array.  |
| using [const_array_iterator](/libpalliate/generated/Files/array_8h#using-const-array-iterator) | **[const_iterator](/libpalliate/generated/Classes/classarray#using-const-iterator)** <br>A RandomAccessIterator for iterating over const elements in a toml::array.  |
| using node | **[value_type](/libpalliate/generated/Classes/classarray#using-value-type)**  |
| using size_t | **[size_type](/libpalliate/generated/Classes/classarray#using-size-type)**  |
| using ptrdiff_t | **[difference_type](/libpalliate/generated/Classes/classarray#using-difference-type)**  |
| using node & | **[reference](/libpalliate/generated/Classes/classarray#using-reference)**  |
| using const node & | **[const_reference](/libpalliate/generated/Classes/classarray#using-const-reference)**  |
| using node | **[value_type](/libpalliate/generated/Classes/classarray#using-value-type)**  |
| using size_t | **[size_type](/libpalliate/generated/Classes/classarray#using-size-type)**  |
| using ptrdiff_t | **[difference_type](/libpalliate/generated/Classes/classarray#using-difference-type)**  |
| using node & | **[reference](/libpalliate/generated/Classes/classarray#using-reference)**  |
| using const node & | **[const_reference](/libpalliate/generated/Classes/classarray#using-const-reference)**  |
| using array_iterator | **[iterator](/libpalliate/generated/Classes/classarray#using-iterator)**  |
| using [const_array_iterator](/libpalliate/generated/Files/array_8h#using-const-array-iterator) | **[const_iterator](/libpalliate/generated/Classes/classarray#using-const-iterator)**  |

## Public Functions

|                | Name           |
| -------------- | -------------- |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter) node_type | **[type](/libpalliate/generated/Classes/classarray#function-type)**() const<br>Returns #toml::node_type::array.  |
| [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter)[TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) bool | **[is_homogeneous](/libpalliate/generated/Classes/classarray#function-is-homogeneous)**(node_type ntype) const |
| [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter)[TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) bool | **[is_homogeneous](/libpalliate/generated/Classes/classarray#function-is-homogeneous)**(node_type ntype, node *& first_nonmatch) |
| [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter)[TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) bool | **[is_homogeneous](/libpalliate/generated/Classes/classarray#function-is-homogeneous)**(node_type ntype, const node *& first_nonmatch) const |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter) bool | **[is_table](/libpalliate/generated/Classes/classarray#function-is-table)**() const<br>Returns `false`.  |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter) bool | **[is_array](/libpalliate/generated/Classes/classarray#function-is-array)**() const<br>Returns `true`.  |
| [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter) bool | **[is_array_of_tables](/libpalliate/generated/Classes/classarray#function-is-array-of-tables)**() const<br>Returns `true` if the array contains only tables.  |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter) bool | **[is_value](/libpalliate/generated/Classes/classarray#function-is-value)**() const<br>Returns `false`.  |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter) bool | **[is_string](/libpalliate/generated/Classes/classarray#function-is-string)**() const<br>Returns `false`.  |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter) bool | **[is_integer](/libpalliate/generated/Classes/classarray#function-is-integer)**() const<br>Returns `false`.  |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter) bool | **[is_floating_point](/libpalliate/generated/Classes/classarray#function-is-floating-point)**() const<br>Returns `false`.  |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter) bool | **[is_number](/libpalliate/generated/Classes/classarray#function-is-number)**() const<br>Returns `false`.  |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter) bool | **[is_boolean](/libpalliate/generated/Classes/classarray#function-is-boolean)**() const<br>Returns `false`.  |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter) bool | **[is_date](/libpalliate/generated/Classes/classarray#function-is-date)**() const<br>Returns `false`.  |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter) bool | **[is_time](/libpalliate/generated/Classes/classarray#function-is-time)**() const<br>Returns `false`.  |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter) bool | **[is_date_time](/libpalliate/generated/Classes/classarray#function-is-date-time)**() const<br>Returns `false`.  |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[table](/libpalliate/generated/Classes/classtable) * | **[as_table](/libpalliate/generated/Classes/classarray#function-as-table)**()<br>Returns `nullptr`.  |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[array](/libpalliate/generated/Classes/classarray) * | **[as_array](/libpalliate/generated/Classes/classarray#function-as-array)**()<br>Returns a pointer to the array.  |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< std::string > * | **[as_string](/libpalliate/generated/Classes/classarray#function-as-string)**()<br>Returns `nullptr`.  |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< int64_t > * | **[as_integer](/libpalliate/generated/Classes/classarray#function-as-integer)**()<br>Returns `nullptr`.  |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< double > * | **[as_floating_point](/libpalliate/generated/Classes/classarray#function-as-floating-point)**()<br>Returns `nullptr`.  |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< bool > * | **[as_boolean](/libpalliate/generated/Classes/classarray#function-as-boolean)**()<br>Returns `nullptr`.  |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< date > * | **[as_date](/libpalliate/generated/Classes/classarray#function-as-date)**()<br>Returns `nullptr`.  |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< [time](/libpalliate/generated/Classes/structtime) > * | **[as_time](/libpalliate/generated/Classes/classarray#function-as-time)**()<br>Returns `nullptr`.  |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< [date_time](/libpalliate/generated/Classes/structdate__time) > * | **[as_date_time](/libpalliate/generated/Classes/classarray#function-as-date-time)**()<br>Returns `nullptr`.  |
| const [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[table](/libpalliate/generated/Classes/classtable) * | **[as_table](/libpalliate/generated/Classes/classarray#function-as-table)**() const<br>Returns `nullptr`.  |
| const [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[array](/libpalliate/generated/Classes/classarray) * | **[as_array](/libpalliate/generated/Classes/classarray#function-as-array)**() const<br>Returns a const-qualified pointer to the array.  |
| const [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< std::string > * | **[as_string](/libpalliate/generated/Classes/classarray#function-as-string)**() const<br>Returns `nullptr`.  |
| const [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< int64_t > * | **[as_integer](/libpalliate/generated/Classes/classarray#function-as-integer)**() const<br>Returns `nullptr`.  |
| const [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< double > * | **[as_floating_point](/libpalliate/generated/Classes/classarray#function-as-floating-point)**() const<br>Returns `nullptr`.  |
| const [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< bool > * | **[as_boolean](/libpalliate/generated/Classes/classarray#function-as-boolean)**() const<br>Returns `nullptr`.  |
| const [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< date > * | **[as_date](/libpalliate/generated/Classes/classarray#function-as-date)**() const<br>Returns `nullptr`.  |
| const [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< [time](/libpalliate/generated/Classes/structtime) > * | **[as_time](/libpalliate/generated/Classes/classarray#function-as-time)**() const<br>Returns `nullptr`.  |
| const [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< [date_time](/libpalliate/generated/Classes/structdate__time) > * | **[as_date_time](/libpalliate/generated/Classes/classarray#function-as-date-time)**() const<br>Returns `nullptr`.  |
| [TOML_PURE_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-inline-getter) node * | **[get](/libpalliate/generated/Classes/classarray#function-get)**(size_t index)<br>Gets a pointer to the element at a specific index.  |
| const [TOML_PURE_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-inline-getter) node * | **[get](/libpalliate/generated/Classes/classarray#function-get)**(size_t index) const<br>Gets a pointer to the element at a specific index (const overload).  |
| template <typename ElemType \> <br>[TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[impl::wrap_node](/libpalliate/generated/Files/toml_8hpp#using-wrap-node)< ElemType > * | **[get_as](/libpalliate/generated/Classes/classarray#function-get-as)**(size_t index)<br>Gets a pointer to the element at a specific index if it is a particular type.  |
| template <typename ElemType \> <br>const [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[impl::wrap_node](/libpalliate/generated/Files/toml_8hpp#using-wrap-node)< ElemType > * | **[get_as](/libpalliate/generated/Classes/classarray#function-get-as)**(size_t index) const<br>Gets a pointer to the element at a specific index if it is a particular type (const overload).  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) node & | **[operator[]](/libpalliate/generated/Classes/classarray#function-operator[])**(size_t index)<br>Gets a reference to the element at a specific index.  |
| const [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) node & | **[operator[]](/libpalliate/generated/Classes/classarray#function-operator[])**(size_t index) const<br>Gets a reference to the element at a specific index.  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) node & | **[at](/libpalliate/generated/Classes/classarray#function-at)**(size_t index)<br>Gets a reference to the element at a specific index, throwing `std::out_of_range` if none existed.  |
| const [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) node & | **[at](/libpalliate/generated/Classes/classarray#function-at)**(size_t index) const<br>Gets a reference to the element at a specific index, throwing `std::out_of_range` if none existed.  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) node & | **[front](/libpalliate/generated/Classes/classarray#function-front)**()<br>Returns a reference to the first element in the array.  |
| const [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) node & | **[front](/libpalliate/generated/Classes/classarray#function-front)**() const<br>Returns a reference to the first element in the array.  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) node & | **[back](/libpalliate/generated/Classes/classarray#function-back)**()<br>Returns a reference to the last element in the array.  |
| const [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) node & | **[back](/libpalliate/generated/Classes/classarray#function-back)**() const<br>Returns a reference to the last element in the array.  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[iterator](/libpalliate/generated/Classes/classarray#using-iterator) | **[begin](/libpalliate/generated/Classes/classarray#function-begin)**()<br>Returns an iterator to the first element.  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[const_iterator](/libpalliate/generated/Classes/classarray#using-const-iterator) | **[begin](/libpalliate/generated/Classes/classarray#function-begin)**() const<br>Returns an iterator to the first element.  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[const_iterator](/libpalliate/generated/Classes/classarray#using-const-iterator) | **[cbegin](/libpalliate/generated/Classes/classarray#function-cbegin)**() const<br>Returns an iterator to the first element.  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[iterator](/libpalliate/generated/Classes/classarray#using-iterator) | **[end](/libpalliate/generated/Classes/classarray#function-end)**()<br>Returns an iterator to one-past-the-last element.  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[const_iterator](/libpalliate/generated/Classes/classarray#using-const-iterator) | **[end](/libpalliate/generated/Classes/classarray#function-end)**() const<br>Returns an iterator to one-past-the-last element.  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[const_iterator](/libpalliate/generated/Classes/classarray#using-const-iterator) | **[cend](/libpalliate/generated/Classes/classarray#function-cend)**() const<br>Returns an iterator to one-past-the-last element.  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) bool | **[empty](/libpalliate/generated/Classes/classarray#function-empty)**() const<br>Returns true if the array is empty.  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) size_t | **[size](/libpalliate/generated/Classes/classarray#function-size)**() const<br>Returns the number of elements in the array.  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) size_t | **[max_size](/libpalliate/generated/Classes/classarray#function-max-size)**() const<br>Returns the maximum number of elements that can be stored in an array on the current platform.  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) size_t | **[capacity](/libpalliate/generated/Classes/classarray#function-capacity)**() const<br>Returns the current max number of elements that may be held in the array's internal storage.  |
| [TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) void | **[reserve](/libpalliate/generated/Classes/classarray#function-reserve)**(size_t new_capacity)<br>Reserves internal storage capacity up to a pre-determined number of elements.  |
| [TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) void | **[shrink_to_fit](/libpalliate/generated/Classes/classarray#function-shrink-to-fit)**()<br>Requests the removal of any unused internal storage capacity.  |
| [TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) void | **[truncate](/libpalliate/generated/Classes/classarray#function-truncate)**(size_t new_size)<br>Shrinks the array to the given size.  |
| template <typename ElemType \> <br>void | **[resize](/libpalliate/generated/Classes/classarray#function-resize)**(size_t new_size, ElemType && default_init_val, [value_flags](/libpalliate/generated/Files/toml_8hpp#variable-value-flags) default_init_flags =[preserve_source_value_flags](/libpalliate/generated/Files/toml_8hpp#variable-preserve-source-value-flags))<br>Resizes the array.  |
| [TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function)[iterator](/libpalliate/generated/Classes/classarray#using-iterator) | **[erase](/libpalliate/generated/Classes/classarray#function-erase)**([const_iterator](/libpalliate/generated/Classes/classarray#using-const-iterator) pos)<br>Removes the specified element from the array.  |
| [TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function)[iterator](/libpalliate/generated/Classes/classarray#using-iterator) | **[erase](/libpalliate/generated/Classes/classarray#function-erase)**([const_iterator](/libpalliate/generated/Classes/classarray#using-const-iterator) first, [const_iterator](/libpalliate/generated/Classes/classarray#using-const-iterator) last)<br>Removes the elements in the range [first, last) from the array.  |
| [TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function)[array](/libpalliate/generated/Classes/classarray) & | **[flatten](/libpalliate/generated/Classes/classarray#function-flatten)**()<br>Flattens this array, recursively hoisting the contents of child arrays up into itself.  |
| [array](/libpalliate/generated/Classes/classarray) && | **[flatten](/libpalliate/generated/Classes/classarray#function-flatten)**()<br>Flattens this array, recursively hoisting the contents of child arrays up into itself (rvalue overload).  |
| [TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function)[array](/libpalliate/generated/Classes/classarray) & | **[prune](/libpalliate/generated/Classes/classarray#function-prune)**(bool recursive =true)<br>Removes empty child arrays and tables.  |
| [array](/libpalliate/generated/Classes/classarray) && | **[prune](/libpalliate/generated/Classes/classarray#function-prune)**(bool recursive =true)<br>Removes empty child arrays and tables (rvalue overload).  |
| [TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) void | **[pop_back](/libpalliate/generated/Classes/classarray#function-pop-back)**()<br>Removes the last element from the array.  |
| [TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) void | **[clear](/libpalliate/generated/Classes/classarray#function-clear)**()<br>Removes all elements from the array.  |
| template <typename ElemType \> <br>[iterator](/libpalliate/generated/Classes/classarray#using-iterator) | **[insert](/libpalliate/generated/Classes/classarray#function-insert)**([const_iterator](/libpalliate/generated/Classes/classarray#using-const-iterator) pos, ElemType && val, [value_flags](/libpalliate/generated/Files/toml_8hpp#variable-value-flags) flags =[preserve_source_value_flags](/libpalliate/generated/Files/toml_8hpp#variable-preserve-source-value-flags))<br>Inserts a new element at a specific position in the array.  |
| template <typename ElemType \> <br>[iterator](/libpalliate/generated/Classes/classarray#using-iterator) | **[insert](/libpalliate/generated/Classes/classarray#function-insert)**([const_iterator](/libpalliate/generated/Classes/classarray#using-const-iterator) pos, size_t count, ElemType && val, [value_flags](/libpalliate/generated/Files/toml_8hpp#variable-value-flags) flags =[preserve_source_value_flags](/libpalliate/generated/Files/toml_8hpp#variable-preserve-source-value-flags))<br>Repeatedly inserts a new element starting at a specific position in the array.  |
| template <typename Iter \> <br>[iterator](/libpalliate/generated/Classes/classarray#using-iterator) | **[insert](/libpalliate/generated/Classes/classarray#function-insert)**([const_iterator](/libpalliate/generated/Classes/classarray#using-const-iterator) pos, Iter first, Iter last, [value_flags](/libpalliate/generated/Files/toml_8hpp#variable-value-flags) flags =[preserve_source_value_flags](/libpalliate/generated/Files/toml_8hpp#variable-preserve-source-value-flags))<br>Inserts a range of elements into the array at a specific position.  |
| template <typename ElemType \> <br>[iterator](/libpalliate/generated/Classes/classarray#using-iterator) | **[insert](/libpalliate/generated/Classes/classarray#function-insert)**([const_iterator](/libpalliate/generated/Classes/classarray#using-const-iterator) pos, std::initializer_list< ElemType > ilist, [value_flags](/libpalliate/generated/Files/toml_8hpp#variable-value-flags) flags =[preserve_source_value_flags](/libpalliate/generated/Files/toml_8hpp#variable-preserve-source-value-flags))<br>Inserts a range of elements into the array at a specific position.  |
| template <typename ElemType ,typename... Args\> <br>[iterator](/libpalliate/generated/Classes/classarray#using-iterator) | **[emplace](/libpalliate/generated/Classes/classarray#function-emplace)**([const_iterator](/libpalliate/generated/Classes/classarray#using-const-iterator) pos, Args &&... args)<br>Emplaces a new element at a specific position in the array.  |
| template <typename ElemType \> <br>[iterator](/libpalliate/generated/Classes/classarray#using-iterator) | **[replace](/libpalliate/generated/Classes/classarray#function-replace)**([const_iterator](/libpalliate/generated/Classes/classarray#using-const-iterator) pos, ElemType && val, [value_flags](/libpalliate/generated/Files/toml_8hpp#variable-value-flags) flags =[preserve_source_value_flags](/libpalliate/generated/Files/toml_8hpp#variable-preserve-source-value-flags))<br>Replaces the element at a specific position in the array with a different value.  |
| template <typename ElemType \> <br>void | **[push_back](/libpalliate/generated/Classes/classarray#function-push-back)**(ElemType && val, [value_flags](/libpalliate/generated/Files/toml_8hpp#variable-value-flags) flags =[preserve_source_value_flags](/libpalliate/generated/Files/toml_8hpp#variable-preserve-source-value-flags))<br>Appends a new element to the end of the array.  |
| template <typename ElemType ,typename... ElemArgs\> <br>decltype(auto) | **[emplace_back](/libpalliate/generated/Classes/classarray#function-emplace-back)**(ElemArgs &&... args)<br>Emplaces a new element at the end of the array.  |
| | **[TOML_ASYMMETRICAL_EQUALITY_OPS](/libpalliate/generated/Classes/classarray#function-toml-asymmetrical-equality-ops)**(const [array](/libpalliate/generated/Classes/classarray) & , const std::initializer_list< T > & , template< typename T > ) |
| | **[TOML_ASYMMETRICAL_EQUALITY_OPS](/libpalliate/generated/Classes/classarray#function-toml-asymmetrical-equality-ops)**(const [array](/libpalliate/generated/Classes/classarray) & , const std::vector< T > & , template< typename T > ) |
| [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor)[TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) | **[array](/libpalliate/generated/Classes/classarray#function-array)**()<br>Default constructor.  |
| [TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) | **[~array](/libpalliate/generated/Classes/classarray#function-~array)**() |
| [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor)[TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) | **[array](/libpalliate/generated/Classes/classarray#function-array)**(const [array](/libpalliate/generated/Classes/classarray) & )<br>Copy constructor.  |
| [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor)[TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) | **[array](/libpalliate/generated/Classes/classarray#function-array)**([array](/libpalliate/generated/Classes/classarray) && other)<br>Move constructor.  |
| | **[TOML_CONSTRAINED_TEMPLATE](/libpalliate/generated/Classes/classarray#function-toml-constrained-template)**((sizeof...(ElemTypes) > 0||!std::is_same_v< impl::remove_cvref< ElemType >, [array](/libpalliate/generated/Classes/classarray) >) , typename ElemType , typename... ElemTypes)<br>Constructs an array with one or more initial elements.  |
| [TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function)[array](/libpalliate/generated/Classes/classarray) & | **[operator=](/libpalliate/generated/Classes/classarray#function-operator=)**([array](/libpalliate/generated/Classes/classarray) && rhs)<br>Move-assignment operator.  |
| [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor)[TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) | **[array](/libpalliate/generated/Classes/classarray#function-array)**() |
| [TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) | **[~array](/libpalliate/generated/Classes/classarray#function-~array)**() |
| [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor)[TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) | **[array](/libpalliate/generated/Classes/classarray#function-array)**(const [array](/libpalliate/generated/Classes/classarray) & ) |
| [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor)[TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) | **[array](/libpalliate/generated/Classes/classarray#function-array)**([array](/libpalliate/generated/Classes/classarray) && other) |
| | **[TOML_CONSTRAINED_TEMPLATE](/libpalliate/generated/Classes/classarray#function-toml-constrained-template)**((sizeof...(ElemTypes) > 0||!std::is_same_v< impl::remove_cvref< ElemType >, [array](/libpalliate/generated/Classes/classarray) >) , typename ElemType , typename... ElemTypes) |
| [TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function)[array](/libpalliate/generated/Classes/classarray) & | **[operator=](/libpalliate/generated/Classes/classarray#function-operator=)**([array](/libpalliate/generated/Classes/classarray) && rhs) |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter) node_type | **[type](/libpalliate/generated/Classes/classarray#function-type)**() const |
| [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter)[TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) bool | **[is_homogeneous](/libpalliate/generated/Classes/classarray#function-is-homogeneous)**(node_type ntype) const |
| [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter)[TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) bool | **[is_homogeneous](/libpalliate/generated/Classes/classarray#function-is-homogeneous)**(node_type ntype, node *& first_nonmatch) |
| [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter)[TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) bool | **[is_homogeneous](/libpalliate/generated/Classes/classarray#function-is-homogeneous)**(node_type ntype, const node *& first_nonmatch) const |
| template <typename ElemType  =void\> <br>[TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter) bool | **[is_homogeneous](/libpalliate/generated/Classes/classarray#function-is-homogeneous)**() const |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter) bool | **[is_table](/libpalliate/generated/Classes/classarray#function-is-table)**() const |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter) bool | **[is_array](/libpalliate/generated/Classes/classarray#function-is-array)**() const |
| [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter) bool | **[is_array_of_tables](/libpalliate/generated/Classes/classarray#function-is-array-of-tables)**() const |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter) bool | **[is_value](/libpalliate/generated/Classes/classarray#function-is-value)**() const |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter) bool | **[is_string](/libpalliate/generated/Classes/classarray#function-is-string)**() const |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter) bool | **[is_integer](/libpalliate/generated/Classes/classarray#function-is-integer)**() const |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter) bool | **[is_floating_point](/libpalliate/generated/Classes/classarray#function-is-floating-point)**() const |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter) bool | **[is_number](/libpalliate/generated/Classes/classarray#function-is-number)**() const |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter) bool | **[is_boolean](/libpalliate/generated/Classes/classarray#function-is-boolean)**() const |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter) bool | **[is_date](/libpalliate/generated/Classes/classarray#function-is-date)**() const |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter) bool | **[is_time](/libpalliate/generated/Classes/classarray#function-is-time)**() const |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter) bool | **[is_date_time](/libpalliate/generated/Classes/classarray#function-is-date-time)**() const |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[table](/libpalliate/generated/Classes/classtable) * | **[as_table](/libpalliate/generated/Classes/classarray#function-as-table)**() |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[array](/libpalliate/generated/Classes/classarray) * | **[as_array](/libpalliate/generated/Classes/classarray#function-as-array)**() |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< std::string > * | **[as_string](/libpalliate/generated/Classes/classarray#function-as-string)**() |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< int64_t > * | **[as_integer](/libpalliate/generated/Classes/classarray#function-as-integer)**() |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< double > * | **[as_floating_point](/libpalliate/generated/Classes/classarray#function-as-floating-point)**() |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< bool > * | **[as_boolean](/libpalliate/generated/Classes/classarray#function-as-boolean)**() |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< date > * | **[as_date](/libpalliate/generated/Classes/classarray#function-as-date)**() |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< [time](/libpalliate/generated/Classes/structtime) > * | **[as_time](/libpalliate/generated/Classes/classarray#function-as-time)**() |
| [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< [date_time](/libpalliate/generated/Classes/structdate__time) > * | **[as_date_time](/libpalliate/generated/Classes/classarray#function-as-date-time)**() |
| const [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[table](/libpalliate/generated/Classes/classtable) * | **[as_table](/libpalliate/generated/Classes/classarray#function-as-table)**() const |
| const [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[array](/libpalliate/generated/Classes/classarray) * | **[as_array](/libpalliate/generated/Classes/classarray#function-as-array)**() const |
| const [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< std::string > * | **[as_string](/libpalliate/generated/Classes/classarray#function-as-string)**() const |
| const [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< int64_t > * | **[as_integer](/libpalliate/generated/Classes/classarray#function-as-integer)**() const |
| const [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< double > * | **[as_floating_point](/libpalliate/generated/Classes/classarray#function-as-floating-point)**() const |
| const [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< bool > * | **[as_boolean](/libpalliate/generated/Classes/classarray#function-as-boolean)**() const |
| const [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< date > * | **[as_date](/libpalliate/generated/Classes/classarray#function-as-date)**() const |
| const [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< [time](/libpalliate/generated/Classes/structtime) > * | **[as_time](/libpalliate/generated/Classes/classarray#function-as-time)**() const |
| const [TOML_CONST_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-const-inline-getter)[toml::value](/libpalliate/generated/Files/toml_8hpp#function-value)< [date_time](/libpalliate/generated/Classes/structdate__time) > * | **[as_date_time](/libpalliate/generated/Classes/classarray#function-as-date-time)**() const |
| [TOML_PURE_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-inline-getter) node * | **[get](/libpalliate/generated/Classes/classarray#function-get)**(size_t index) |
| const [TOML_PURE_INLINE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-inline-getter) node * | **[get](/libpalliate/generated/Classes/classarray#function-get)**(size_t index) const |
| template <typename ElemType \> <br>[TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[impl::wrap_node](/libpalliate/generated/Files/toml_8hpp#using-wrap-node)< ElemType > * | **[get_as](/libpalliate/generated/Classes/classarray#function-get-as)**(size_t index) |
| template <typename ElemType \> <br>const [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[impl::wrap_node](/libpalliate/generated/Files/toml_8hpp#using-wrap-node)< ElemType > * | **[get_as](/libpalliate/generated/Classes/classarray#function-get-as)**(size_t index) const |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) node & | **[operator[]](/libpalliate/generated/Classes/classarray#function-operator[])**(size_t index) |
| const [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) node & | **[operator[]](/libpalliate/generated/Classes/classarray#function-operator[])**(size_t index) const |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) node & | **[at](/libpalliate/generated/Classes/classarray#function-at)**(size_t index) |
| const [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) node & | **[at](/libpalliate/generated/Classes/classarray#function-at)**(size_t index) const |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) node & | **[front](/libpalliate/generated/Classes/classarray#function-front)**() |
| const [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) node & | **[front](/libpalliate/generated/Classes/classarray#function-front)**() const |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) node & | **[back](/libpalliate/generated/Classes/classarray#function-back)**() |
| const [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) node & | **[back](/libpalliate/generated/Classes/classarray#function-back)**() const |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[iterator](/libpalliate/generated/Classes/classarray#using-iterator) | **[begin](/libpalliate/generated/Classes/classarray#function-begin)**() |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[const_iterator](/libpalliate/generated/Classes/classarray#using-const-iterator) | **[begin](/libpalliate/generated/Classes/classarray#function-begin)**() const |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[const_iterator](/libpalliate/generated/Classes/classarray#using-const-iterator) | **[cbegin](/libpalliate/generated/Classes/classarray#function-cbegin)**() const |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[iterator](/libpalliate/generated/Classes/classarray#using-iterator) | **[end](/libpalliate/generated/Classes/classarray#function-end)**() |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[const_iterator](/libpalliate/generated/Classes/classarray#using-const-iterator) | **[end](/libpalliate/generated/Classes/classarray#function-end)**() const |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[const_iterator](/libpalliate/generated/Classes/classarray#using-const-iterator) | **[cend](/libpalliate/generated/Classes/classarray#function-cend)**() const |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) bool | **[empty](/libpalliate/generated/Classes/classarray#function-empty)**() const |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) size_t | **[size](/libpalliate/generated/Classes/classarray#function-size)**() const |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) size_t | **[max_size](/libpalliate/generated/Classes/classarray#function-max-size)**() const |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) size_t | **[capacity](/libpalliate/generated/Classes/classarray#function-capacity)**() const |
| [TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) void | **[reserve](/libpalliate/generated/Classes/classarray#function-reserve)**(size_t new_capacity) |
| [TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) void | **[shrink_to_fit](/libpalliate/generated/Classes/classarray#function-shrink-to-fit)**() |
| [TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) void | **[truncate](/libpalliate/generated/Classes/classarray#function-truncate)**(size_t new_size) |
| template <typename ElemType \> <br>void | **[resize](/libpalliate/generated/Classes/classarray#function-resize)**(size_t new_size, ElemType && default_init_val, [value_flags](/libpalliate/generated/Files/toml_8hpp#variable-value-flags) default_init_flags =[preserve_source_value_flags](/libpalliate/generated/Files/toml_8hpp#variable-preserve-source-value-flags)) |
| [TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function)[iterator](/libpalliate/generated/Classes/classarray#using-iterator) | **[erase](/libpalliate/generated/Classes/classarray#function-erase)**([const_iterator](/libpalliate/generated/Classes/classarray#using-const-iterator) pos) |
| [TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function)[iterator](/libpalliate/generated/Classes/classarray#using-iterator) | **[erase](/libpalliate/generated/Classes/classarray#function-erase)**([const_iterator](/libpalliate/generated/Classes/classarray#using-const-iterator) first, [const_iterator](/libpalliate/generated/Classes/classarray#using-const-iterator) last) |
| [TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function)[array](/libpalliate/generated/Classes/classarray) & | **[flatten](/libpalliate/generated/Classes/classarray#function-flatten)**() |
| [array](/libpalliate/generated/Classes/classarray) && | **[flatten](/libpalliate/generated/Classes/classarray#function-flatten)**() |
| [TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function)[array](/libpalliate/generated/Classes/classarray) & | **[prune](/libpalliate/generated/Classes/classarray#function-prune)**(bool recursive =true) |
| [array](/libpalliate/generated/Classes/classarray) && | **[prune](/libpalliate/generated/Classes/classarray#function-prune)**(bool recursive =true) |
| [TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) void | **[pop_back](/libpalliate/generated/Classes/classarray#function-pop-back)**() |
| [TOML_EXPORTED_MEMBER_FUNCTION](/libpalliate/generated/Files/toml_8hpp#define-toml-exported-member-function) void | **[clear](/libpalliate/generated/Classes/classarray#function-clear)**() |
| template <typename ElemType \> <br>[iterator](/libpalliate/generated/Classes/classarray#using-iterator) | **[insert](/libpalliate/generated/Classes/classarray#function-insert)**([const_iterator](/libpalliate/generated/Classes/classarray#using-const-iterator) pos, ElemType && val, [value_flags](/libpalliate/generated/Files/toml_8hpp#variable-value-flags) flags =[preserve_source_value_flags](/libpalliate/generated/Files/toml_8hpp#variable-preserve-source-value-flags)) |
| template <typename ElemType \> <br>[iterator](/libpalliate/generated/Classes/classarray#using-iterator) | **[insert](/libpalliate/generated/Classes/classarray#function-insert)**([const_iterator](/libpalliate/generated/Classes/classarray#using-const-iterator) pos, size_t count, ElemType && val, [value_flags](/libpalliate/generated/Files/toml_8hpp#variable-value-flags) flags =[preserve_source_value_flags](/libpalliate/generated/Files/toml_8hpp#variable-preserve-source-value-flags)) |
| template <typename Iter \> <br>[iterator](/libpalliate/generated/Classes/classarray#using-iterator) | **[insert](/libpalliate/generated/Classes/classarray#function-insert)**([const_iterator](/libpalliate/generated/Classes/classarray#using-const-iterator) pos, Iter first, Iter last, [value_flags](/libpalliate/generated/Files/toml_8hpp#variable-value-flags) flags =[preserve_source_value_flags](/libpalliate/generated/Files/toml_8hpp#variable-preserve-source-value-flags)) |
| template <typename ElemType \> <br>[iterator](/libpalliate/generated/Classes/classarray#using-iterator) | **[insert](/libpalliate/generated/Classes/classarray#function-insert)**([const_iterator](/libpalliate/generated/Classes/classarray#using-const-iterator) pos, std::initializer_list< ElemType > ilist, [value_flags](/libpalliate/generated/Files/toml_8hpp#variable-value-flags) flags =[preserve_source_value_flags](/libpalliate/generated/Files/toml_8hpp#variable-preserve-source-value-flags)) |
| template <typename ElemType ,typename... Args\> <br>[iterator](/libpalliate/generated/Classes/classarray#using-iterator) | **[emplace](/libpalliate/generated/Classes/classarray#function-emplace)**([const_iterator](/libpalliate/generated/Classes/classarray#using-const-iterator) pos, Args &&... args) |
| template <typename ElemType \> <br>[iterator](/libpalliate/generated/Classes/classarray#using-iterator) | **[replace](/libpalliate/generated/Classes/classarray#function-replace)**([const_iterator](/libpalliate/generated/Classes/classarray#using-const-iterator) pos, ElemType && val, [value_flags](/libpalliate/generated/Files/toml_8hpp#variable-value-flags) flags =[preserve_source_value_flags](/libpalliate/generated/Files/toml_8hpp#variable-preserve-source-value-flags)) |
| template <typename ElemType \> <br>void | **[push_back](/libpalliate/generated/Classes/classarray#function-push-back)**(ElemType && val, [value_flags](/libpalliate/generated/Files/toml_8hpp#variable-value-flags) flags =[preserve_source_value_flags](/libpalliate/generated/Files/toml_8hpp#variable-preserve-source-value-flags)) |
| template <typename ElemType ,typename... ElemArgs\> <br>decltype(auto) | **[emplace_back](/libpalliate/generated/Classes/classarray#function-emplace-back)**(ElemArgs &&... args) |
| | **[TOML_ASYMMETRICAL_EQUALITY_OPS](/libpalliate/generated/Classes/classarray#function-toml-asymmetrical-equality-ops)**(const [array](/libpalliate/generated/Classes/classarray) & , const std::initializer_list< T > & , template< typename T > ) |
| | **[TOML_ASYMMETRICAL_EQUALITY_OPS](/libpalliate/generated/Classes/classarray#function-toml-asymmetrical-equality-ops)**(const [array](/libpalliate/generated/Classes/classarray) & , const std::vector< T > & , template< typename T > ) |

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| ElemTypes && | **[vals](/libpalliate/generated/Classes/classarray#variable-vals)**  |

## Friends

|                | Name           |
| -------------- | -------------- |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) friend bool | **[operator==](/libpalliate/generated/Classes/classarray#friend-operator==)**(const [array](/libpalliate/generated/Classes/classarray) & lhs, const [array](/libpalliate/generated/Classes/classarray) & rhs) <br>Equality operator.  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) friend bool | **[operator!=](/libpalliate/generated/Classes/classarray#friend-operator!=)**(const [array](/libpalliate/generated/Classes/classarray) & lhs, const [array](/libpalliate/generated/Classes/classarray) & rhs) <br>Inequality operator.  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) friend bool | **[operator==](/libpalliate/generated/Classes/classarray#friend-operator==)**(const [array](/libpalliate/generated/Classes/classarray) & lhs, const std::initializer_list< T > & rhs) <br>Initializer list equality operator.  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) friend bool | **[operator==](/libpalliate/generated/Classes/classarray#friend-operator==)**(const [array](/libpalliate/generated/Classes/classarray) & lhs, const std::vector< T > & rhs) <br>Vector equality operator.  |
| std::ostream & | **[operator<<](/libpalliate/generated/Classes/classarray#friend-operator<<)**(std::ostream & lhs, const [array](/libpalliate/generated/Classes/classarray) & rhs) <br>Prints the array out to a stream as formatted TOML.  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) friend bool | **[operator==](/libpalliate/generated/Classes/classarray#friend-operator==)**(const [array](/libpalliate/generated/Classes/classarray) & lhs, const [array](/libpalliate/generated/Classes/classarray) & rhs)  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) friend bool | **[operator!=](/libpalliate/generated/Classes/classarray#friend-operator!=)**(const [array](/libpalliate/generated/Classes/classarray) & lhs, const [array](/libpalliate/generated/Classes/classarray) & rhs)  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) friend bool | **[operator==](/libpalliate/generated/Classes/classarray#friend-operator==)**(const [array](/libpalliate/generated/Classes/classarray) & lhs, const std::initializer_list< T > & rhs)  |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard) friend bool | **[operator==](/libpalliate/generated/Classes/classarray#friend-operator==)**(const [array](/libpalliate/generated/Classes/classarray) & lhs, const std::vector< T > & rhs)  |
| std::ostream & | **[operator<<](/libpalliate/generated/Classes/classarray#friend-operator<<)**(std::ostream & lhs, const [array](/libpalliate/generated/Classes/classarray) & rhs)  |

## Detailed Description

```cpp
class array;
```

A TOML array. 

\detail The interface of this type is modeled after std::vector, with some additional considerations made for the heterogeneous nature of a TOML array.

\godbolt{sjK4da}

\cpp

toml::table tbl = toml::parse(R"( arr = [1, 2, 3, 4, 'five'] )"sv);

// get the element as an array toml::array& arr = *tbl.[get_as<toml::array>](/libpalliate/generated/Classes/classarray#function-get-as)("arr"); std::cout << arr << "\n";

// increment each element with visit() for (auto&& elem : arr) { elem.visit([](auto&& el) noexcept { if constexpr (toml::is_number<decltype(el)>) (*el)++; else if constexpr (toml::is_string<decltype(el)>) el = "six"sv; }); } std::cout << arr << "\n";

// add and remove elements arr.push_back(7); arr.push_back(8.0f); arr.push_back("nine"sv); arr.erase(arr.cbegin()); std::cout << arr << "\n";

// emplace elements arr.emplace_back<std::string>("ten"); arr.emplace_back<toml::array>(11, 12.0); std::cout << arr << "\n"; \ecpp

\out [ 1, 2, 3, 4, 'five' ] [ 2, 3, 4, 5, 'six' ] [ 3, 4, 5, 'six', 7, 8.0, 'nine' ] [ 3, 4, 5, 'six', 7, 8.0, 'nine', 'ten', [ 11, 12.0 ] ] \eout 

## Public Types Documentation

### using iterator

```cpp
using array::iterator =  array_iterator;
```

A RandomAccessIterator for iterating over elements in a toml::array. 

### using const_iterator

```cpp
using array::const_iterator =  const_array_iterator;
```

A RandomAccessIterator for iterating over const elements in a toml::array. 

### using value_type

```cpp
using array::value_type =  node;
```


### using size_type

```cpp
using array::size_type =  size_t;
```


### using difference_type

```cpp
using array::difference_type =  ptrdiff_t;
```


### using reference

```cpp
using array::reference =  node&;
```


### using const_reference

```cpp
using array::const_reference =  const node&;
```


### using value_type

```cpp
using array::value_type =  node;
```


### using size_type

```cpp
using array::size_type =  size_t;
```


### using difference_type

```cpp
using array::difference_type =  ptrdiff_t;
```


### using reference

```cpp
using array::reference =  node&;
```


### using const_reference

```cpp
using array::const_reference =  const node&;
```


### using iterator

```cpp
using array::iterator =  array_iterator;
```


### using const_iterator

```cpp
using array::const_iterator =  const_array_iterator;
```


## Public Functions Documentation

### function type

```cpp
inline TOML_CONST_INLINE_GETTER node_type type() const
```

Returns #toml::node_type::array. 

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

Returns `false`. 

### function is_array

```cpp
inline TOML_CONST_INLINE_GETTER bool is_array() const
```

Returns `true`. 

### function is_array_of_tables

```cpp
inline TOML_PURE_GETTER bool is_array_of_tables() const
```

Returns `true` if the array contains only tables. 

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

Returns `nullptr`. 

### function as_array

```cpp
inline TOML_CONST_INLINE_GETTERarray * as_array()
```

Returns a pointer to the array. 

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

Returns `nullptr`. 

### function as_array

```cpp
inline const TOML_CONST_INLINE_GETTERarray * as_array() const
```

Returns a const-qualified pointer to the array. 

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

### function get

```cpp
inline TOML_PURE_INLINE_GETTER node * get(
    size_t index
)
```

Gets a pointer to the element at a specific index. 

**Parameters**: 

  * **index** The element's index.


**Return**: A pointer to the element at the specified index if one existed, or nullptr. 

\detail \cpp auto arr = toml::array{ 99, "bottles of beer on the wall" }; std::cout << "element [0] exists: "sv << !!arr.get(0) << "\n"; std::cout << "element [1] exists: "sv << !!arr.get(1) << "\n"; std::cout << "element [2] exists: "sv << !!arr.get(2) << "\n"; if (toml::node* val = arr.get(0)) std::cout << "element [0] is an "sv << val->[type()](/libpalliate/generated/Classes/classarray#function-type) << "\n"; \ecpp

\out element [0] exists: true element [1] exists: true element [2] exists: false element [0] is an integer \eout


### function get

```cpp
inline const TOML_PURE_INLINE_GETTER node * get(
    size_t index
) const
```

Gets a pointer to the element at a specific index (const overload). 

**Parameters**: 

  * **index** The element's index.


**Return**: A pointer to the element at the specified index if one existed, or nullptr. 

### function get_as

```cpp
template <typename ElemType >
inline TOML_NODISCARDimpl::wrap_node< ElemType > * get_as(
    size_t index
)
```

Gets a pointer to the element at a specific index if it is a particular type. 

**Parameters**: 

  * **index** The element's index.


**Template Parameters**: 

  * **ElemType** toml::table, toml::array, or a native TOML value type 


**Return**: A pointer to the selected element if it existed and was of the specified type, or nullptr. 

\detail \cpp auto arr = toml::array{ 42, "is the meaning of life, apparently."sv }; if (toml::value<int64_t>* val = arr.get_as<int64_t>(0)) std::cout << "element [0] is an integer with value "sv << *val << "\n"; \ecpp

\out element [0] is an integer with value 42 \eout


### function get_as

```cpp
template <typename ElemType >
inline const TOML_NODISCARDimpl::wrap_node< ElemType > * get_as(
    size_t index
) const
```

Gets a pointer to the element at a specific index if it is a particular type (const overload). 

**Parameters**: 

  * **index** The element's index.


**Template Parameters**: 

  * **ElemType** toml::table, toml::array, or a native TOML value type 


**Return**: A pointer to the selected element if it existed and was of the specified type, or nullptr. 

### function operator[]

```cpp
inline TOML_NODISCARD node & operator[](
    size_t index
)
```

Gets a reference to the element at a specific index. 

### function operator[]

```cpp
inline const TOML_NODISCARD node & operator[](
    size_t index
) const
```

Gets a reference to the element at a specific index. 

### function at

```cpp
TOML_NODISCARDTOML_EXPORTED_MEMBER_FUNCTION node & at(
    size_t index
)
```

Gets a reference to the element at a specific index, throwing `std::out_of_range` if none existed. 

### function at

```cpp
inline const TOML_NODISCARD node & at(
    size_t index
) const
```

Gets a reference to the element at a specific index, throwing `std::out_of_range` if none existed. 

### function front

```cpp
inline TOML_NODISCARD node & front()
```

Returns a reference to the first element in the array. 

### function front

```cpp
inline const TOML_NODISCARD node & front() const
```

Returns a reference to the first element in the array. 

### function back

```cpp
inline TOML_NODISCARD node & back()
```

Returns a reference to the last element in the array. 

### function back

```cpp
inline const TOML_NODISCARD node & back() const
```

Returns a reference to the last element in the array. 

### function begin

```cpp
inline TOML_NODISCARDiterator begin()
```

Returns an iterator to the first element. 

### function begin

```cpp
inline TOML_NODISCARDconst_iterator begin() const
```

Returns an iterator to the first element. 

### function cbegin

```cpp
inline TOML_NODISCARDconst_iterator cbegin() const
```

Returns an iterator to the first element. 

### function end

```cpp
inline TOML_NODISCARDiterator end()
```

Returns an iterator to one-past-the-last element. 

### function end

```cpp
inline TOML_NODISCARDconst_iterator end() const
```

Returns an iterator to one-past-the-last element. 

### function cend

```cpp
inline TOML_NODISCARDconst_iterator cend() const
```

Returns an iterator to one-past-the-last element. 

### function empty

```cpp
inline TOML_NODISCARD bool empty() const
```

Returns true if the array is empty. 

### function size

```cpp
inline TOML_NODISCARD size_t size() const
```

Returns the number of elements in the array. 

### function max_size

```cpp
inline TOML_NODISCARD size_t max_size() const
```

Returns the maximum number of elements that can be stored in an array on the current platform. 

### function capacity

```cpp
inline TOML_NODISCARD size_t capacity() const
```

Returns the current max number of elements that may be held in the array's internal storage. 

### function reserve

```cpp
TOML_EXPORTED_MEMBER_FUNCTION void reserve(
    size_t new_capacity
)
```

Reserves internal storage capacity up to a pre-determined number of elements. 

### function shrink_to_fit

```cpp
TOML_EXPORTED_MEMBER_FUNCTION void shrink_to_fit()
```

Requests the removal of any unused internal storage capacity. 

### function truncate

```cpp
TOML_EXPORTED_MEMBER_FUNCTION void truncate(
    size_t new_size
)
```

Shrinks the array to the given size. 

**Remark**: Does nothing if the requested size is larger than or equal to the current size. 

\detail \godbolt{rxEzK5}

\cpp auto arr = toml::array{ 1, 2, 3 }; std::cout << arr << "\n";

arr.truncate(5); // no-op std::cout << arr << "\n";

arr.truncate(1); std::cout << arr << "\n"; \ecpp

\out [ 1, 2, 3 ] [ 1, 2, 3 ] [ 1] \eout


### function resize

```cpp
template <typename ElemType >
inline void resize(
    size_t new_size,
    ElemType && default_init_val,
    value_flags default_init_flags =preserve_source_value_flags
)
```

Resizes the array. 

**Parameters**: 

  * **new_size** The number of elements the array will have after resizing. 
  * **default_init_val** The node or value used to initialize new elements if the array needs to grow. 
  * **default_init_flags** Value flags to apply to new values created if new elements are created by growing. 


**Template Parameters**: 

  * **ElemType** toml::node, toml::table, toml::array, or a native TOML value type (or a type promotable to one).


\detail \godbolt{W5zqx3}

\cpp auto arr = toml::array{ 1, 2, 3 }; std::cout << arr << "\n";

arr.resize(6, 42); std::cout << arr << "\n";

arr.resize(2, 0); std::cout << arr << "\n"; \ecpp

\out [ 1, 2, 3 ] [ 1, 2, 3, 42, 42, 42 ] [ 1, 2 ] \eout


### function erase

```cpp
TOML_EXPORTED_MEMBER_FUNCTIONiterator erase(
    const_iterator pos
)
```

Removes the specified element from the array. 

**Parameters**: 

  * **pos** Iterator to the element being erased.


**Return**: Iterator to the first element immediately following the removed element. 

\detail \cpp auto arr = toml::array{ 1, 2, 3 }; std::cout << arr << "\n";

arr.erase(arr.cbegin() + 1); std::cout << arr << "\n"; \ecpp

\out [ 1, 2, 3 ] [ 1, 3 ] \eout


### function erase

```cpp
TOML_EXPORTED_MEMBER_FUNCTIONiterator erase(
    const_iterator first,
    const_iterator last
)
```

Removes the elements in the range [first, last) from the array. 

**Parameters**: 

  * **first** Iterator to the first element being erased. 
  * **last** Iterator to the one-past-the-last element being erased.


**Return**: Iterator to the first element immediately following the last removed element. 

\detail \cpp auto arr = toml::array{ 1, "bad", "karma" 2 }; std::cout << arr << "\n";

arr.erase(arr.cbegin() + 1, arr.cbegin() + 3); std::cout << arr << "\n"; \ecpp

\out [ 1, 'bad', 'karma', 3 ] [ 1, 3 ] \eout


### function flatten

```cpp
TOML_EXPORTED_MEMBER_FUNCTIONarray & flatten()
```

Flattens this array, recursively hoisting the contents of child arrays up into itself. 

**Return**: A reference to the array. 

**Remark**: Arrays inside child tables are not flattened.

\detail \cpp

auto arr = toml::array{ 1, 2, toml::array{ 3, 4, toml::array{ 5 } }, 6, toml::array{} }; std::cout << arr << "\n";

arr.flatten(); std::cout << arr << "\n"; \ecpp

\out [ 1, 2, [ 3, 4, [ 5 ] ], 6, [] ] [ 1, 2, 3, 4, 5, 6 ] \eout


### function flatten

```cpp
inline array && flatten()
```

Flattens this array, recursively hoisting the contents of child arrays up into itself (rvalue overload). 

**Return**: An rvalue reference to the array. 

### function prune

```cpp
TOML_EXPORTED_MEMBER_FUNCTIONarray & prune(
    bool recursive =true
)
```

Removes empty child arrays and tables. 

**Parameters**: 

  * **recursive** Should child arrays and tables themselves be pruned?


**Return**: A reference to the array. 

\detail \cpp

auto arr = toml::array{ 1, 2, toml::array{ }, toml::array{ 3, toml::array{ } }, 4 }; std::cout << arr << "\n";

arr.prune(true); std::cout << arr << "\n"; \ecpp

\out [ 1, 2, [], [ 3, [] ], 4 ] [ 1, 2, [ 3 ], 4 ] \eout


### function prune

```cpp
inline array && prune(
    bool recursive =true
)
```

Removes empty child arrays and tables (rvalue overload). 

**Parameters**: 

  * **recursive** Should child arrays and tables themselves be pruned?


**Return**: An rvalue reference to the array. 

### function pop_back

```cpp
TOML_EXPORTED_MEMBER_FUNCTION void pop_back()
```

Removes the last element from the array. 

### function clear

```cpp
TOML_EXPORTED_MEMBER_FUNCTION void clear()
```

Removes all elements from the array. 

### function insert

```cpp
template <typename ElemType >
inline iterator insert(
    const_iterator pos,
    ElemType && val,
    value_flags flags =preserve_source_value_flags
)
```

Inserts a new element at a specific position in the array. 

**Parameters**: 

  * **pos** The insertion position. 
  * **val** The node or value being inserted. 
  * **flags** Value flags to apply to new values.


**Template Parameters**: 

  * **ElemType** toml::node, toml::node_view, toml::table, toml::array, or a native TOML value type (or a type promotable to one). 


**Return**: \conditional_return{Valid input} An iterator to the newly-inserted element. \conditional_return{Input is a null toml::node_view} [end()](/libpalliate/generated/Classes/classarray#function-end)

**Attention**: The return value will always be `[end()](/libpalliate/generated/Classes/classarray#function-end)` if the input value was a null toml::node_view, because no insertion can take place. This is the only circumstance in which this can occur. 

\detail \cpp auto arr = toml::array{ 1, 3 }; arr.insert(arr.cbegin() + 1, "two"); arr.insert(arr.cend(), toml::array{ 4, 5 }); std::cout << arr << "\n"; \ecpp

\out [ 1, 'two', 3, [ 4, 5 ] ] \eout


### function insert

```cpp
template <typename ElemType >
inline iterator insert(
    const_iterator pos,
    size_t count,
    ElemType && val,
    value_flags flags =preserve_source_value_flags
)
```

Repeatedly inserts a new element starting at a specific position in the array. 

**Parameters**: 

  * **pos** The insertion position. 
  * **count** The number of times the node or value should be inserted. 
  * **val** The node or value being inserted. 
  * **flags** Value flags to apply to new values.


**Template Parameters**: 

  * **ElemType** toml::node, toml::node_view, toml::table, toml::array, or a native TOML value type (or a type promotable to one). 


**Return**: \conditional_return{Valid input} An iterator to the newly-inserted element. \conditional_return{count == 0} A copy of pos \conditional_return{Input is a null toml::node_view} [end()](/libpalliate/generated/Classes/classarray#function-end)

**Attention**: The return value will always be `[end()](/libpalliate/generated/Classes/classarray#function-end)` if the input value was a null toml::node_view, because no insertion can take place. This is the only circumstance in which this can occur. 

\detail \cpp auto arr = toml::array{ "with an evil twinkle in its eye the goose said", "and immediately we knew peace was never an option." }; arr.insert(arr.cbegin() + 1, 3, "honk"); std::cout << arr << "\n"; \ecpp

\out [ 'with an evil twinkle in its eye the goose said', 'honk', 'honk', 'honk', 'and immediately we knew peace was never an option.' ] \eout


### function insert

```cpp
template <typename Iter >
inline iterator insert(
    const_iterator pos,
    Iter first,
    Iter last,
    value_flags flags =preserve_source_value_flags
)
```

Inserts a range of elements into the array at a specific position. 

**Parameters**: 

  * **pos** The insertion position. 
  * **first** Iterator to the first node or value being inserted. 
  * **last** Iterator to the one-past-the-last node or value being inserted. 
  * **flags** Value flags to apply to new values.


**Template Parameters**: 

  * **Iter** An iterator type. Must satisfy ForwardIterator. 


**Return**: \conditional_return{Valid input} An iterator to the first newly-inserted element. \conditional_return{first >= last} A copy of pos \conditional_return{All objects in the range were null toml::node_views} A copy of pos 

### function insert

```cpp
template <typename ElemType >
inline iterator insert(
    const_iterator pos,
    std::initializer_list< ElemType > ilist,
    value_flags flags =preserve_source_value_flags
)
```

Inserts a range of elements into the array at a specific position. 

**Parameters**: 

  * **pos** The insertion position. 
  * **ilist** An initializer list containing the values to be inserted. 
  * **flags** Value flags to apply to new values.


**Template Parameters**: 

  * **ElemType** toml::node_view, toml::table, toml::array, or a native TOML value type (or a type promotable to one). 


**Return**: \conditional_return{Valid input} An iterator to the first newly-inserted element. \conditional_return{Input list is empty} A copy of pos \conditional_return{All objects in the list were null toml::node_views} A copy of pos 

### function emplace

```cpp
template <typename ElemType ,
typename... Args>
inline iterator emplace(
    const_iterator pos,
    Args &&... args
)
```

Emplaces a new element at a specific position in the array. 

**Parameters**: 

  * **pos** The insertion position. 
  * **args** Arguments to forward to the value's constructor.


**Template Parameters**: 

  * **ElemType** toml::table, toml::array, or any native TOML value type. 
  * **Args** Value constructor argument types. 


**Return**: An iterator to the inserted element.

**Remark**: There is no difference between [insert()](/libpalliate/generated/Classes/classarray#function-insert) and [emplace()](/libpalliate/generated/Classes/classarray#function-emplace) for trivial value types (floats, ints, bools). 

\detail \cpp auto arr = toml::array{ 1, 2 };

//add a string using std::string's substring constructor arr.emplace<std::string>(arr.cbegin() + 1, "this is not a drill"sv, 14, 5); std::cout << arr << "\n"; \ecpp

\out [ 1, 'drill', 2 ] \eout


### function replace

```cpp
template <typename ElemType >
inline iterator replace(
    const_iterator pos,
    ElemType && val,
    value_flags flags =preserve_source_value_flags
)
```

Replaces the element at a specific position in the array with a different value. 

**Parameters**: 

  * **pos** The insertion position. 
  * **val** The node or value being inserted. 
  * **flags** Value flags to apply to new values.


**Template Parameters**: 

  * **ElemType** toml::node, toml::node_view, toml::table, toml::array, or a native TOML value type (or a type promotable to one). 


**Return**: \conditional_return{Valid input} An iterator to the replaced element. \conditional_return{Input is a null toml::node_view} [end()](/libpalliate/generated/Classes/classarray#function-end)

**Attention**: The return value will always be `[end()](/libpalliate/generated/Classes/classarray#function-end)` if the input value was a null toml::node_view, because no replacement can take place. This is the only circumstance in which this can occur. 

\detail \cpp auto arr = toml::array{ 1, 2, 3 }; std::cout << arr << "\n"; arr.replace(arr.cbegin() + 1, "two"); std::cout << arr << "\n"; \ecpp

\out [ 1, 2, 3 ] [ 1, 'two', 3 ] \eout


### function push_back

```cpp
template <typename ElemType >
inline void push_back(
    ElemType && val,
    value_flags flags =preserve_source_value_flags
)
```

Appends a new element to the end of the array. 

**Parameters**: 

  * **val** The node or value being added. 
  * **flags** Value flags to apply to new values.


**Template Parameters**: 

  * **ElemType** toml::node, toml::node_view, toml::table, toml::array, or a native TOML value type 


**Attention**: No insertion takes place if the input value is a null toml::node_view. This is the only circumstance in which this can occur. 

\detail \cpp auto arr = toml::array{ 1, 2 }; arr.push_back(3); arr.push_back(4.0); arr.push_back(toml::array{ 5, "six"sv }); std::cout << arr << "\n"; \ecpp

\out [ 1, 2, 3, 4.0, [ 5, 'six' ] ] \eout


### function emplace_back

```cpp
template <typename ElemType ,
typename... ElemArgs>
inline decltype(auto) emplace_back(
    ElemArgs &&... args
)
```

Emplaces a new element at the end of the array. 

**Parameters**: 

  * **args** Arguments to forward to the elements's constructor.


**Template Parameters**: 

  * **ElemType** toml::table, toml::array, or a native TOML value type 
  * **ElemArgs** Element constructor argument types. 


**Return**: A reference to the newly-constructed element.

**Remark**: There is no difference between [push_back()](/libpalliate/generated/Classes/classarray#function-push-back) and [emplace_back()](/libpalliate/generated/Classes/classarray#function-emplace-back) For trivial value types (floats, ints, bools). 

\detail \cpp auto arr = toml::array{ 1, 2 }; arr.emplace_back<toml::array>(3, "four"sv); std::cout << arr << "\n"; \ecpp

\out [ 1, 2, [ 3, 'four' ] ] \eout


### function TOML_ASYMMETRICAL_EQUALITY_OPS

```cpp
TOML_ASYMMETRICAL_EQUALITY_OPS(
    const array & ,
    const std::initializer_list< T > & ,
    template< typename T > 
)
```


### function TOML_ASYMMETRICAL_EQUALITY_OPS

```cpp
TOML_ASYMMETRICAL_EQUALITY_OPS(
    const array & ,
    const std::vector< T > & ,
    template< typename T > 
)
```


### function array

```cpp
TOML_NODISCARD_CTORTOML_EXPORTED_MEMBER_FUNCTION array()
```

Default constructor. 

### function ~array

```cpp
TOML_EXPORTED_MEMBER_FUNCTION ~array()
```


### function array

```cpp
TOML_NODISCARD_CTORTOML_EXPORTED_MEMBER_FUNCTION array(
    const array & 
)
```

Copy constructor. 

### function array

```cpp
TOML_NODISCARD_CTORTOML_EXPORTED_MEMBER_FUNCTION array(
    array && other
)
```

Move constructor. 

### function TOML_CONSTRAINED_TEMPLATE

```cpp
TOML_CONSTRAINED_TEMPLATE(
    (sizeof...(ElemTypes) > 0||!std::is_same_v< impl::remove_cvref< ElemType >, array >) ,
    typename ElemType ,
    typename... ElemTypes
)
```

Constructs an array with one or more initial elements. 

**Parameters**: 

  * **val** The node or value used to initialize element 0. 
  * **vals** The nodes or values used to initialize elements 1...N. 


**Template Parameters**: 

  * **ElemType** One of the TOML node or value types (or a type promotable to one). 
  * **ElemTypes** One of the TOML node or value types (or a type promotable to one). 


**Remark**: If you need to construct an array with one child array element, the array's move constructor will take precedence and perform a move-construction instead. You can use toml::inserter to suppress this behaviour: \cpp // desired result: [ [ 42 ] ] auto bad = toml::array{ toml::array{ 42 } } auto good = toml::array{ toml::inserter{ toml::array{ 42 } } } std::cout << "bad: " << bad << "\n"; std::cout << "good:" << good << "\n"; \ecpp

\out bad: [ 42 ] good: [ [ 42 ] ] \eout

\detail \cpp auto arr = toml::array{ 1, 2.0, "three"sv, toml::array{ 4, 5 } }; std::cout << arr << "\n"; \ecpp

\out [ 1, 2.0, 'three', [ 4, 5 ] ] \eout


### function operator=

```cpp
TOML_EXPORTED_MEMBER_FUNCTIONarray & operator=(
    array && rhs
)
```

Move-assignment operator. 

### function array

```cpp
TOML_NODISCARD_CTORTOML_EXPORTED_MEMBER_FUNCTION array()
```


### function ~array

```cpp
TOML_EXPORTED_MEMBER_FUNCTION ~array()
```


### function array

```cpp
TOML_NODISCARD_CTORTOML_EXPORTED_MEMBER_FUNCTION array(
    const array & 
)
```


### function array

```cpp
TOML_NODISCARD_CTORTOML_EXPORTED_MEMBER_FUNCTION array(
    array && other
)
```


### function TOML_CONSTRAINED_TEMPLATE

```cpp
TOML_CONSTRAINED_TEMPLATE(
    (sizeof...(ElemTypes) > 0||!std::is_same_v< impl::remove_cvref< ElemType >, array >) ,
    typename ElemType ,
    typename... ElemTypes
)
```


**Parameters**: 

  * **val** The node or value used to initialize element 0. 
  * **vals** The nodes or values used to initialize elements 1...N. 


**Template Parameters**: 

  * **ElemType** One of the TOML node or value types (or a type promotable to one). 
  * **ElemTypes** One of the TOML node or value types (or a type promotable to one). 


**Remark**: If you need to construct an array with one child array element, the array's move constructor will take precedence and perform a move-construction instead. You can use toml::inserter to suppress this behaviour: \cpp // desired result: [ [ 42 ] ] auto bad = toml::array{ toml::array{ 42 } } auto good = toml::array{ toml::inserter{ toml::array{ 42 } } } std::cout << "bad: " << bad << "\n"; std::cout << "good:" << good << "\n"; \ecpp

\out bad: [ 42 ] good: [ [ 42 ] ] \eout

\detail \cpp auto arr = toml::array{ 1, 2.0, "three"sv, toml::array{ 4, 5 } }; std::cout << arr << "\n"; \ecpp

\out [ 1, 2.0, 'three', [ 4, 5 ] ] \eout


### function operator=

```cpp
TOML_EXPORTED_MEMBER_FUNCTIONarray & operator=(
    array && rhs
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


### function get

```cpp
inline TOML_PURE_INLINE_GETTER node * get(
    size_t index
)
```


**Parameters**: 

  * **index** The element's index.


**Return**: A pointer to the element at the specified index if one existed, or nullptr. 

\detail \cpp auto arr = toml::array{ 99, "bottles of beer on the wall" }; std::cout << "element [0] exists: "sv << !!arr.get(0) << "\n"; std::cout << "element [1] exists: "sv << !!arr.get(1) << "\n"; std::cout << "element [2] exists: "sv << !!arr.get(2) << "\n"; if (toml::node* val = arr.get(0)) std::cout << "element [0] is an "sv << val->[type()](/libpalliate/generated/Classes/classarray#function-type) << "\n"; \ecpp

\out element [0] exists: true element [1] exists: true element [2] exists: false element [0] is an integer \eout


### function get

```cpp
inline const TOML_PURE_INLINE_GETTER node * get(
    size_t index
) const
```


**Parameters**: 

  * **index** The element's index.


**Return**: A pointer to the element at the specified index if one existed, or nullptr. 

### function get_as

```cpp
template <typename ElemType >
inline TOML_NODISCARDimpl::wrap_node< ElemType > * get_as(
    size_t index
)
```


**Parameters**: 

  * **index** The element's index.


**Template Parameters**: 

  * **ElemType** toml::table, toml::array, or a native TOML value type 


**Return**: A pointer to the selected element if it existed and was of the specified type, or nullptr. 

\detail \cpp auto arr = toml::array{ 42, "is the meaning of life, apparently."sv }; if (toml::value<int64_t>* val = arr.get_as<int64_t>(0)) std::cout << "element [0] is an integer with value "sv << *val << "\n"; \ecpp

\out element [0] is an integer with value 42 \eout


### function get_as

```cpp
template <typename ElemType >
inline const TOML_NODISCARDimpl::wrap_node< ElemType > * get_as(
    size_t index
) const
```


**Parameters**: 

  * **index** The element's index.


**Template Parameters**: 

  * **ElemType** toml::table, toml::array, or a native TOML value type 


**Return**: A pointer to the selected element if it existed and was of the specified type, or nullptr. 

### function operator[]

```cpp
inline TOML_NODISCARD node & operator[](
    size_t index
)
```


### function operator[]

```cpp
inline const TOML_NODISCARD node & operator[](
    size_t index
) const
```


### function at

```cpp
TOML_NODISCARDTOML_EXPORTED_MEMBER_FUNCTION node & at(
    size_t index
)
```


### function at

```cpp
inline const TOML_NODISCARD node & at(
    size_t index
) const
```


### function front

```cpp
inline TOML_NODISCARD node & front()
```


### function front

```cpp
inline const TOML_NODISCARD node & front() const
```


### function back

```cpp
inline TOML_NODISCARD node & back()
```


### function back

```cpp
inline const TOML_NODISCARD node & back() const
```


### function begin

```cpp
inline TOML_NODISCARDiterator begin()
```


### function begin

```cpp
inline TOML_NODISCARDconst_iterator begin() const
```


### function cbegin

```cpp
inline TOML_NODISCARDconst_iterator cbegin() const
```


### function end

```cpp
inline TOML_NODISCARDiterator end()
```


### function end

```cpp
inline TOML_NODISCARDconst_iterator end() const
```


### function cend

```cpp
inline TOML_NODISCARDconst_iterator cend() const
```


### function empty

```cpp
inline TOML_NODISCARD bool empty() const
```


### function size

```cpp
inline TOML_NODISCARD size_t size() const
```


### function max_size

```cpp
inline TOML_NODISCARD size_t max_size() const
```


### function capacity

```cpp
inline TOML_NODISCARD size_t capacity() const
```


### function reserve

```cpp
TOML_EXPORTED_MEMBER_FUNCTION void reserve(
    size_t new_capacity
)
```


### function shrink_to_fit

```cpp
TOML_EXPORTED_MEMBER_FUNCTION void shrink_to_fit()
```


### function truncate

```cpp
TOML_EXPORTED_MEMBER_FUNCTION void truncate(
    size_t new_size
)
```


**Remark**: Does nothing if the requested size is larger than or equal to the current size. 

\detail \godbolt{rxEzK5}

\cpp auto arr = toml::array{ 1, 2, 3 }; std::cout << arr << "\n";

arr.truncate(5); // no-op std::cout << arr << "\n";

arr.truncate(1); std::cout << arr << "\n"; \ecpp

\out [ 1, 2, 3 ] [ 1, 2, 3 ] [ 1] \eout


### function resize

```cpp
template <typename ElemType >
inline void resize(
    size_t new_size,
    ElemType && default_init_val,
    value_flags default_init_flags =preserve_source_value_flags
)
```


**Parameters**: 

  * **new_size** The number of elements the array will have after resizing. 
  * **default_init_val** The node or value used to initialize new elements if the array needs to grow. 
  * **default_init_flags** Value flags to apply to new values created if new elements are created by growing. 


**Template Parameters**: 

  * **ElemType** toml::node, toml::table, toml::array, or a native TOML value type (or a type promotable to one).


\detail \godbolt{W5zqx3}

\cpp auto arr = toml::array{ 1, 2, 3 }; std::cout << arr << "\n";

arr.resize(6, 42); std::cout << arr << "\n";

arr.resize(2, 0); std::cout << arr << "\n"; \ecpp

\out [ 1, 2, 3 ] [ 1, 2, 3, 42, 42, 42 ] [ 1, 2 ] \eout


### function erase

```cpp
TOML_EXPORTED_MEMBER_FUNCTIONiterator erase(
    const_iterator pos
)
```


**Parameters**: 

  * **pos** Iterator to the element being erased.


**Return**: Iterator to the first element immediately following the removed element. 

\detail \cpp auto arr = toml::array{ 1, 2, 3 }; std::cout << arr << "\n";

arr.erase(arr.cbegin() + 1); std::cout << arr << "\n"; \ecpp

\out [ 1, 2, 3 ] [ 1, 3 ] \eout


### function erase

```cpp
TOML_EXPORTED_MEMBER_FUNCTIONiterator erase(
    const_iterator first,
    const_iterator last
)
```


**Parameters**: 

  * **first** Iterator to the first element being erased. 
  * **last** Iterator to the one-past-the-last element being erased.


**Return**: Iterator to the first element immediately following the last removed element. 

\detail \cpp auto arr = toml::array{ 1, "bad", "karma" 2 }; std::cout << arr << "\n";

arr.erase(arr.cbegin() + 1, arr.cbegin() + 3); std::cout << arr << "\n"; \ecpp

\out [ 1, 'bad', 'karma', 3 ] [ 1, 3 ] \eout


### function flatten

```cpp
TOML_EXPORTED_MEMBER_FUNCTIONarray & flatten()
```


**Return**: A reference to the array. 

**Remark**: Arrays inside child tables are not flattened.

\detail \cpp

auto arr = toml::array{ 1, 2, toml::array{ 3, 4, toml::array{ 5 } }, 6, toml::array{} }; std::cout << arr << "\n";

arr.flatten(); std::cout << arr << "\n"; \ecpp

\out [ 1, 2, [ 3, 4, [ 5 ] ], 6, [] ] [ 1, 2, 3, 4, 5, 6 ] \eout


### function flatten

```cpp
inline array && flatten()
```


**Return**: An rvalue reference to the array. 

### function prune

```cpp
TOML_EXPORTED_MEMBER_FUNCTIONarray & prune(
    bool recursive =true
)
```


**Parameters**: 

  * **recursive** Should child arrays and tables themselves be pruned?


**Return**: A reference to the array. 

\detail \cpp

auto arr = toml::array{ 1, 2, toml::array{ }, toml::array{ 3, toml::array{ } }, 4 }; std::cout << arr << "\n";

arr.prune(true); std::cout << arr << "\n"; \ecpp

\out [ 1, 2, [], [ 3, [] ], 4 ] [ 1, 2, [ 3 ], 4 ] \eout


### function prune

```cpp
inline array && prune(
    bool recursive =true
)
```


**Parameters**: 

  * **recursive** Should child arrays and tables themselves be pruned?


**Return**: An rvalue reference to the array. 

### function pop_back

```cpp
TOML_EXPORTED_MEMBER_FUNCTION void pop_back()
```


### function clear

```cpp
TOML_EXPORTED_MEMBER_FUNCTION void clear()
```


### function insert

```cpp
template <typename ElemType >
inline iterator insert(
    const_iterator pos,
    ElemType && val,
    value_flags flags =preserve_source_value_flags
)
```


**Parameters**: 

  * **pos** The insertion position. 
  * **val** The node or value being inserted. 
  * **flags** Value flags to apply to new values.


**Template Parameters**: 

  * **ElemType** toml::node, toml::node_view, toml::table, toml::array, or a native TOML value type (or a type promotable to one). 


**Return**: \conditional_return{Valid input} An iterator to the newly-inserted element. \conditional_return{Input is a null toml::node_view} [end()](/libpalliate/generated/Classes/classarray#function-end)

**Attention**: The return value will always be `[end()](/libpalliate/generated/Classes/classarray#function-end)` if the input value was a null toml::node_view, because no insertion can take place. This is the only circumstance in which this can occur. 

\detail \cpp auto arr = toml::array{ 1, 3 }; arr.insert(arr.cbegin() + 1, "two"); arr.insert(arr.cend(), toml::array{ 4, 5 }); std::cout << arr << "\n"; \ecpp

\out [ 1, 'two', 3, [ 4, 5 ] ] \eout


### function insert

```cpp
template <typename ElemType >
inline iterator insert(
    const_iterator pos,
    size_t count,
    ElemType && val,
    value_flags flags =preserve_source_value_flags
)
```


**Parameters**: 

  * **pos** The insertion position. 
  * **count** The number of times the node or value should be inserted. 
  * **val** The node or value being inserted. 
  * **flags** Value flags to apply to new values.


**Template Parameters**: 

  * **ElemType** toml::node, toml::node_view, toml::table, toml::array, or a native TOML value type (or a type promotable to one). 


**Return**: \conditional_return{Valid input} An iterator to the newly-inserted element. \conditional_return{count == 0} A copy of pos \conditional_return{Input is a null toml::node_view} [end()](/libpalliate/generated/Classes/classarray#function-end)

**Attention**: The return value will always be `[end()](/libpalliate/generated/Classes/classarray#function-end)` if the input value was a null toml::node_view, because no insertion can take place. This is the only circumstance in which this can occur. 

\detail \cpp auto arr = toml::array{ "with an evil twinkle in its eye the goose said", "and immediately we knew peace was never an option." }; arr.insert(arr.cbegin() + 1, 3, "honk"); std::cout << arr << "\n"; \ecpp

\out [ 'with an evil twinkle in its eye the goose said', 'honk', 'honk', 'honk', 'and immediately we knew peace was never an option.' ] \eout


### function insert

```cpp
template <typename Iter >
inline iterator insert(
    const_iterator pos,
    Iter first,
    Iter last,
    value_flags flags =preserve_source_value_flags
)
```


**Parameters**: 

  * **pos** The insertion position. 
  * **first** Iterator to the first node or value being inserted. 
  * **last** Iterator to the one-past-the-last node or value being inserted. 
  * **flags** Value flags to apply to new values.


**Template Parameters**: 

  * **Iter** An iterator type. Must satisfy ForwardIterator. 


**Return**: \conditional_return{Valid input} An iterator to the first newly-inserted element. \conditional_return{first >= last} A copy of pos \conditional_return{All objects in the range were null toml::node_views} A copy of pos 

### function insert

```cpp
template <typename ElemType >
inline iterator insert(
    const_iterator pos,
    std::initializer_list< ElemType > ilist,
    value_flags flags =preserve_source_value_flags
)
```


**Parameters**: 

  * **pos** The insertion position. 
  * **ilist** An initializer list containing the values to be inserted. 
  * **flags** Value flags to apply to new values.


**Template Parameters**: 

  * **ElemType** toml::node_view, toml::table, toml::array, or a native TOML value type (or a type promotable to one). 


**Return**: \conditional_return{Valid input} An iterator to the first newly-inserted element. \conditional_return{Input list is empty} A copy of pos \conditional_return{All objects in the list were null toml::node_views} A copy of pos 

### function emplace

```cpp
template <typename ElemType ,
typename... Args>
inline iterator emplace(
    const_iterator pos,
    Args &&... args
)
```


**Parameters**: 

  * **pos** The insertion position. 
  * **args** Arguments to forward to the value's constructor.


**Template Parameters**: 

  * **ElemType** toml::table, toml::array, or any native TOML value type. 
  * **Args** Value constructor argument types. 


**Return**: An iterator to the inserted element.

**Remark**: There is no difference between [insert()](/libpalliate/generated/Classes/classarray#function-insert) and [emplace()](/libpalliate/generated/Classes/classarray#function-emplace) for trivial value types (floats, ints, bools). 

\detail \cpp auto arr = toml::array{ 1, 2 };

//add a string using std::string's substring constructor arr.emplace<std::string>(arr.cbegin() + 1, "this is not a drill"sv, 14, 5); std::cout << arr << "\n"; \ecpp

\out [ 1, 'drill', 2 ] \eout


### function replace

```cpp
template <typename ElemType >
inline iterator replace(
    const_iterator pos,
    ElemType && val,
    value_flags flags =preserve_source_value_flags
)
```


**Parameters**: 

  * **pos** The insertion position. 
  * **val** The node or value being inserted. 
  * **flags** Value flags to apply to new values.


**Template Parameters**: 

  * **ElemType** toml::node, toml::node_view, toml::table, toml::array, or a native TOML value type (or a type promotable to one). 


**Return**: \conditional_return{Valid input} An iterator to the replaced element. \conditional_return{Input is a null toml::node_view} [end()](/libpalliate/generated/Classes/classarray#function-end)

**Attention**: The return value will always be `[end()](/libpalliate/generated/Classes/classarray#function-end)` if the input value was a null toml::node_view, because no replacement can take place. This is the only circumstance in which this can occur. 

\detail \cpp auto arr = toml::array{ 1, 2, 3 }; std::cout << arr << "\n"; arr.replace(arr.cbegin() + 1, "two"); std::cout << arr << "\n"; \ecpp

\out [ 1, 2, 3 ] [ 1, 'two', 3 ] \eout


### function push_back

```cpp
template <typename ElemType >
inline void push_back(
    ElemType && val,
    value_flags flags =preserve_source_value_flags
)
```


**Parameters**: 

  * **val** The node or value being added. 
  * **flags** Value flags to apply to new values.


**Template Parameters**: 

  * **ElemType** toml::node, toml::node_view, toml::table, toml::array, or a native TOML value type 


**Attention**: No insertion takes place if the input value is a null toml::node_view. This is the only circumstance in which this can occur. 

\detail \cpp auto arr = toml::array{ 1, 2 }; arr.push_back(3); arr.push_back(4.0); arr.push_back(toml::array{ 5, "six"sv }); std::cout << arr << "\n"; \ecpp

\out [ 1, 2, 3, 4.0, [ 5, 'six' ] ] \eout


### function emplace_back

```cpp
template <typename ElemType ,
typename... ElemArgs>
inline decltype(auto) emplace_back(
    ElemArgs &&... args
)
```


**Parameters**: 

  * **args** Arguments to forward to the elements's constructor.


**Template Parameters**: 

  * **ElemType** toml::table, toml::array, or a native TOML value type 
  * **ElemArgs** Element constructor argument types. 


**Return**: A reference to the newly-constructed element.

**Remark**: There is no difference between [push_back()](/libpalliate/generated/Classes/classarray#function-push-back) and [emplace_back()](/libpalliate/generated/Classes/classarray#function-emplace-back) For trivial value types (floats, ints, bools). 

\detail \cpp auto arr = toml::array{ 1, 2 }; arr.emplace_back<toml::array>(3, "four"sv); std::cout << arr << "\n"; \ecpp

\out [ 1, 2, [ 3, 'four' ] ] \eout


### function TOML_ASYMMETRICAL_EQUALITY_OPS

```cpp
TOML_ASYMMETRICAL_EQUALITY_OPS(
    const array & ,
    const std::initializer_list< T > & ,
    template< typename T > 
)
```


### function TOML_ASYMMETRICAL_EQUALITY_OPS

```cpp
TOML_ASYMMETRICAL_EQUALITY_OPS(
    const array & ,
    const std::vector< T > & ,
    template< typename T > 
)
```


## Public Attributes Documentation

### variable vals

```cpp
ElemTypes && vals;
```


## Friends

### friend operator==

```cpp
friend TOML_NODISCARD friend bool operator==(
    const array & lhs,

    const array & rhs
);
```

Equality operator. 

**Parameters**: 

  * **lhs** The LHS array. 
  * **rhs** The RHS array.


**Return**: True if the arrays contained the same elements. 

### friend operator!=

```cpp
friend TOML_NODISCARD friend bool operator!=(
    const array & lhs,

    const array & rhs
);
```

Inequality operator. 

**Parameters**: 

  * **lhs** The LHS array. 
  * **rhs** The RHS array.


**Return**: True if the arrays did not contain the same elements. 

### friend operator==

```cpp
friend TOML_NODISCARD friend bool operator==(
    const array & lhs,

    const std::initializer_list< T > & rhs
);
```

Initializer list equality operator. 

### friend operator==

```cpp
friend TOML_NODISCARD friend bool operator==(
    const array & lhs,

    const std::vector< T > & rhs
);
```

Vector equality operator. 

### friend operator<<

```cpp
friend std::ostream & operator<<(
    std::ostream & lhs,

    const array & rhs
);
```

Prints the array out to a stream as formatted TOML. 

\availability This operator is only available when [TOML_ENABLE_FORMATTERS](/libpalliate/generated/Files/toml_8hpp#define-toml-enable-formatters) is enabled. 


### friend operator==

```cpp
friend TOML_NODISCARD friend bool operator==(
    const array & lhs,

    const array & rhs
);
```


**Parameters**: 

  * **lhs** The LHS array. 
  * **rhs** The RHS array.


**Return**: True if the arrays contained the same elements. 

### friend operator!=

```cpp
friend TOML_NODISCARD friend bool operator!=(
    const array & lhs,

    const array & rhs
);
```


**Parameters**: 

  * **lhs** The LHS array. 
  * **rhs** The RHS array.


**Return**: True if the arrays did not contain the same elements. 

### friend operator==

```cpp
friend TOML_NODISCARD friend bool operator==(
    const array & lhs,

    const std::initializer_list< T > & rhs
);
```


### friend operator==

```cpp
friend TOML_NODISCARD friend bool operator==(
    const array & lhs,

    const std::vector< T > & rhs
);
```


### friend operator<<

```cpp
friend std::ostream & operator<<(
    std::ostream & lhs,

    const array & rhs
);
```


\availability This operator is only available when [TOML_ENABLE_FORMATTERS](/libpalliate/generated/Files/toml_8hpp#define-toml-enable-formatters) is enabled. 



_Automatically updated on 2022-05-02 at 01:42:07 +0000._