---
title: generate_conformance_tests
parent: Namespaces
grand_parent: libpalliate
layout: default
---

# generate_conformance_tests



## Classes

|                | Name           |
| -------------- | -------------- |
| class | **[generate_conformance_tests::TomlPPArray](/libpalliate/generated/Classes/classgenerate__conformance__tests_1_1TomlPPArray)**  |
| class | **[generate_conformance_tests::TomlPPTable](/libpalliate/generated/Classes/classgenerate__conformance__tests_1_1TomlPPTable)**  |
| class | **[generate_conformance_tests::TomlTest](/libpalliate/generated/Classes/classgenerate__conformance__tests_1_1TomlTest)**  |

## Functions

|                | Name           |
| -------------- | -------------- |
| def | **[sanitize](/libpalliate/generated/Namespaces/namespacegenerate__conformance__tests#function-sanitize)**(s s) |
| def | **[is_problematic_control_char](/libpalliate/generated/Namespaces/namespacegenerate__conformance__tests#function-is-problematic-control-char)**(val val) |
| def | **[has_problematic_control_chars](/libpalliate/generated/Namespaces/namespacegenerate__conformance__tests#function-has-problematic-control-chars)**(val val) |
| def | **[requires_unicode](/libpalliate/generated/Namespaces/namespacegenerate__conformance__tests#function-requires-unicode)**(s s) |
| def | **[make_string_literal](/libpalliate/generated/Namespaces/namespacegenerate__conformance__tests#function-make-string-literal)**(val val, escape_all escape_all =False, escape_any escape_any =False) |
| def | **[python_value_to_tomlpp](/libpalliate/generated/Namespaces/namespacegenerate__conformance__tests#function-python-value-to-tomlpp)**(val val) |
| def | **[json_to_python](/libpalliate/generated/Namespaces/namespacegenerate__conformance__tests#function-json-to-python)**(val val) |
| def | **[python_to_tomlpp](/libpalliate/generated/Namespaces/namespacegenerate__conformance__tests#function-python-to-tomlpp)**(node node) |
| def | **[load_tests](/libpalliate/generated/Namespaces/namespacegenerate__conformance__tests#function-load-tests)**(source_folder source_folder, is_valid_set is_valid_set, ignore_list ignore_list =None) |
| def | **[add_condition](/libpalliate/generated/Namespaces/namespacegenerate__conformance__tests#function-add-condition)**(tests tests, condition condition, names names) |
| def | **[load_valid_inputs](/libpalliate/generated/Namespaces/namespacegenerate__conformance__tests#function-load-valid-inputs)**(tests tests, extern_root extern_root) |
| def | **[load_invalid_inputs](/libpalliate/generated/Namespaces/namespacegenerate__conformance__tests#function-load-invalid-inputs)**(tests tests, extern_root extern_root) |
| def | **[write_test_file](/libpalliate/generated/Namespaces/namespacegenerate__conformance__tests#function-write-test-file)**(name name, all_tests all_tests) |

## Attributes

|                | Name           |
| -------------- | -------------- |
| | **[main](/libpalliate/generated/Namespaces/namespacegenerate__conformance__tests#variable-main)**  |
| | **[verbose](/libpalliate/generated/Namespaces/namespacegenerate__conformance__tests#variable-verbose)**  |


## Functions Documentation

### function sanitize

```python
def sanitize(
    s s
)
```


### function is_problematic_control_char

```python
def is_problematic_control_char(
    val val
)
```


### function has_problematic_control_chars

```python
def has_problematic_control_chars(
    val val
)
```


### function requires_unicode

```python
def requires_unicode(
    s s
)
```


### function make_string_literal

```python
def make_string_literal(
    val val,
    escape_all escape_all =False,
    escape_any escape_any =False
)
```


### function python_value_to_tomlpp

```python
def python_value_to_tomlpp(
    val val
)
```


### function json_to_python

```python
def json_to_python(
    val val
)
```


### function python_to_tomlpp

```python
def python_to_tomlpp(
    node node
)
```


### function load_tests

```python
def load_tests(
    source_folder source_folder,
    is_valid_set is_valid_set,
    ignore_list ignore_list =None
)
```


### function add_condition

```python
def add_condition(
    tests tests,
    condition condition,
    names names
)
```


### function load_valid_inputs

```python
def load_valid_inputs(
    tests tests,
    extern_root extern_root
)
```


### function load_invalid_inputs

```python
def load_invalid_inputs(
    tests tests,
    extern_root extern_root
)
```


### function write_test_file

```python
def write_test_file(
    name name,
    all_tests all_tests
)
```



## Attributes Documentation

### variable main

```python
main;
```


### variable verbose

```python
verbose;
```






_Automatically updated on 2022-05-02 at 01:42:11 +0000._