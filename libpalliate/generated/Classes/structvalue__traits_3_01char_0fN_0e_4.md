---
title: value_traits< char[N]>
parent: Classes
grand_parent: libpalliate
layout: default
---

# value_traits< char[N]>



 [More...](#detailed-description)


`#include <toml.hpp>`

Inherits from [string_value_traits< char[N]>](/libpalliate/generated/Classes/structstring__value__traits)

## Additional inherited members

**Public Types inherited from [string_value_traits< char[N]>](/libpalliate/generated/Classes/structstring__value__traits)**

|                | Name           |
| -------------- | -------------- |
| using std::string | **[native_type](/libpalliate/generated/Classes/structstring__value__traits#using-native-type)**  |

**Public Attributes inherited from [string_value_traits< char[N]>](/libpalliate/generated/Classes/structstring__value__traits)**

|                | Name           |
| -------------- | -------------- |
| constexpr bool | **[is_native](/libpalliate/generated/Classes/structstring__value__traits#variable-is-native)**  |
| constexpr bool | **[is_losslessly_convertible_to_native](/libpalliate/generated/Classes/structstring__value__traits#variable-is-losslessly-convertible-to-native)**  |
| constexpr bool | **[can_represent_native](/libpalliate/generated/Classes/structstring__value__traits#variable-can-represent-native)**  |
| constexpr bool | **[can_partially_represent_native](/libpalliate/generated/Classes/structstring__value__traits#variable-can-partially-represent-native)**  |
| constexpr auto | **[type](/libpalliate/generated/Classes/structstring__value__traits#variable-type)**  |


## Detailed Description

```cpp
template <size_t N>
struct value_traits< char[N]>;
```


_Automatically updated on 2022-05-02 at 01:42:07 +0000._