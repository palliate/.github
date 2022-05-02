---
title: literals
parent: Namespaces
grand_parent: libpalliate
layout: default
---

# literals



## Functions

|                | Name           |
| -------------- | -------------- |
| | **[TOML_ABI_NAMESPACE_BOOL](/libpalliate/generated/Namespaces/namespaceliterals#function-toml-abi-namespace-bool)**([TOML_EXCEPTIONS](/libpalliate/generated/Files/toml_8hpp#define-toml-exceptions) , lit_ex , lit_noex ) |
| [TOML_NODISCARD](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard)[parse_result](/libpalliate/generated/Classes/classparse__result) | **[operator""_toml](/libpalliate/generated/Namespaces/namespaceliterals#function-operator""-toml)**(const char * str, size_t len)<br>Parses TOML data from a string literal.  |

## Attributes

|                | Name           |
| -------------- | -------------- |
| | **[TOML_ABI_NAMESPACE_END](/libpalliate/generated/Namespaces/namespaceliterals#variable-toml-abi-namespace-end)**  |


## Functions Documentation

### function TOML_ABI_NAMESPACE_BOOL

```cpp
TOML_ABI_NAMESPACE_BOOL(
    TOML_EXCEPTIONS ,
    lit_ex ,
    lit_noex 
)
```


### function operator""_toml

```cpp
inline TOML_NODISCARDparse_result operator""_toml(
    const char * str,
    size_t len
)
```

Parses TOML data from a string literal. 

**Parameters**: 

  * **str** The string data. Must be valid UTF-8. 
  * **len** The string length.


**Return**: \conditional_return{With exceptions} A toml::table. \conditional_return{Without exceptions} A toml::parse_result. 

\detail \cpp using namespace toml::literals;

auto tbl = "a = 3"_toml; std::cout << tbl["a"] << "\n"; \ecpp

\out 3 \eout



## Attributes Documentation

### variable TOML_ABI_NAMESPACE_END

```cpp
TOML_ABI_NAMESPACE_END;
```






_Automatically updated on 2022-05-02 at 01:42:07 +0000._