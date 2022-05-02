---
title: integer_value_traits< T, false >
parent: Classes
grand_parent: libpalliate
layout: default
---

# integer_value_traits< T, false >



 [More...](#detailed-description)


`#include <toml.hpp>`

Inherits from [unsigned_integer_value_traits< T >](/libpalliate/generated/Classes/structunsigned__integer__value__traits), [integer_value_traits_base< T >](/libpalliate/generated/Classes/structinteger__value__traits__base), [integer_value_limits< T >](/libpalliate/generated/Classes/structinteger__value__limits)

## Additional inherited members

**Public Attributes inherited from [unsigned_integer_value_traits< T >](/libpalliate/generated/Classes/structunsigned__integer__value__traits)**

|                | Name           |
| -------------- | -------------- |
| constexpr bool | **[is_losslessly_convertible_to_native](/libpalliate/generated/Classes/structunsigned__integer__value__traits#variable-is-losslessly-convertible-to-native)**  |
| constexpr bool | **[can_represent_native](/libpalliate/generated/Classes/structunsigned__integer__value__traits#variable-can-represent-native)**  |

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
struct integer_value_traits< T, false >;
```


_Automatically updated on 2022-05-02 at 01:42:11 +0000._