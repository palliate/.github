---
title: inserter
summary: Helper class for suppressing move-construction in single-argument array constructors. 
parent: Classes
grand_parent: libpalliate
layout: default
---

# inserter



Helper class for suppressing move-construction in single-argument array constructors.  [More...](#detailed-description)


`#include <toml.hpp>`

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| T | **[value](/libpalliate/generated/Classes/structinserter#variable-value)**  |

## Detailed Description

```cpp
template <typename T >
struct inserter;
```

Helper class for suppressing move-construction in single-argument array constructors. 

**See**: toml::array 

\detail \cpp // desired result: [ [ 42 ] ] auto bad = toml::array{ toml::array{ 42 } } auto good = toml::array{ toml::inserter{ toml::array{ 42 } } } std::cout << "bad: " << bad << "\n"; std::cout << "good:" << good << "\n"; \ecpp \out bad: [ 42 ] good: [ [ 42 ] ] \eout

## Public Attributes Documentation

### variable value

```cpp
T value;
```



_Automatically updated on 2022-05-02 at 01:42:11 +0000._