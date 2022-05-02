---
title: unsigned_integer_value_traits
parent: Classes
grand_parent: libpalliate
layout: default
---

# unsigned_integer_value_traits



 [More...](#detailed-description)


`#include <toml.hpp>`

Inherits from [integer_value_traits_base< T >](/libpalliate/generated/Classes/structinteger__value__traits__base), [integer_value_limits< T >](/libpalliate/generated/Classes/structinteger__value__limits)

Inherited by [integer_value_traits< T, false >](/libpalliate/generated/Classes/structinteger__value__traits_3_01T_00_01false_01_4)

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| constexpr bool | **[is_losslessly_convertible_to_native](/libpalliate/generated/Classes/structunsigned__integer__value__traits#variable-is-losslessly-convertible-to-native)**  |
| constexpr bool | **[can_represent_native](/libpalliate/generated/Classes/structunsigned__integer__value__traits#variable-can-represent-native)**  |

## Additional inherited members

**Public Types inherited from [integer_value_traits_base< T >](/libpalliate/generated/Classes/structinteger__value__traits__base)**

|                | Name           |
| -------------- | -------------- |
| using int64_t | **[native_type](/libpalliate/generated/Classes/structinteger__value__traits__base#using-native-type)**  |

**Public Attributes inherited from [integer_value_traits_base< T >](/libpalliate/generated/Classes/structinteger__value__traits__base)**

|                | Name           |
| -------------- | -------------- |
| constexpr bool | **[is_native](/libpalliate/generated/Classes/structinteger__value__traits__base#variable-is-native)**  |
| constexpr bool | **[is_signed](/libpalliate/generated/Classes/structinteger__value__traits__base#variable-is-signed)**  |
| constexpr auto | **[type](/libpalliate/generated/Classes/structinteger__value__traits__base#variable-type)**  |
| constexpr bool | **[can_partially_represent_native](/libpalliate/generated/Classes/structinteger__value__traits__base#variable-can-partially-represent-native)**  |

**Public Attributes inherited from [integer_value_limits< T >](/libpalliate/generated/Classes/structinteger__value__limits)**

|                | Name           |
| -------------- | -------------- |
| constexpr auto | **[min](/libpalliate/generated/Classes/structinteger__value__limits#variable-min)**  |
| constexpr auto | **[max](/libpalliate/generated/Classes/structinteger__value__limits#variable-max)**  |


## Detailed Description

```cpp
template <typename T >
struct unsigned_integer_value_traits;
```

## Public Attributes Documentation

### variable is_losslessly_convertible_to_native

```cpp
static constexpr bool is_losslessly_convertible_to_native =
			integer_value_limits<T>::max <= 9223372036854775807ULL;
```


### variable can_represent_native

```cpp
static constexpr bool can_represent_native = false;
```



_Automatically updated on 2022-05-02 at 01:42:07 +0000._