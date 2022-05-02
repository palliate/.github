---
title: time
summary: A local time-of-day. 
parent: Classes
grand_parent: libpalliate
layout: default
---

# time



A local time-of-day. 


`#include <toml.hpp>`

## Public Functions

|                | Name           |
| -------------- | -------------- |
| [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor) | **[time](/libpalliate/generated/Classes/structtime#function-time)**() =default<br>Default constructor. Does not initialize the members.  |
| | **[TOML_CONSTRAINED_TEMPLATE](/libpalliate/generated/Classes/structtime#function-toml-constrained-template)**(([impl::all_integral](/libpalliate/generated/Files/toml_8hpp#variable-all-integral)< H, M, S, NS >) , typename H , typename M , typename S  =uint8_t, typename NS  =uint32_t) const<br>Constructs a time from individual time component values.  |
| [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor) | **[time](/libpalliate/generated/Classes/structtime#function-time)**() =default |
| | **[TOML_CONSTRAINED_TEMPLATE](/libpalliate/generated/Classes/structtime#function-toml-constrained-template)**(([impl::all_integral](/libpalliate/generated/Files/toml_8hpp#variable-all-integral)< H, M, S, NS >) , typename H , typename M , typename S  =uint8_t, typename NS  =uint32_t) const |

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| uint8_t | **[hour](/libpalliate/generated/Classes/structtime#variable-hour)** <br>The hour component, from 0 - 23.  |
| uint8_t | **[minute](/libpalliate/generated/Classes/structtime#variable-minute)** <br>The minute component, from 0 - 59.  |
| uint8_t | **[second](/libpalliate/generated/Classes/structtime#variable-second)** <br>The second component, from 0 - 59.  |
| uint32_t | **[nanosecond](/libpalliate/generated/Classes/structtime#variable-nanosecond)** <br>The fractional nanoseconds component, from 0 - 999999999.  |
| M | **[m](/libpalliate/generated/Classes/structtime#variable-m)**  |
| M S | **[s](/libpalliate/generated/Classes/structtime#variable-s)**  |

## Public Functions Documentation

### function time

```cpp
TOML_NODISCARD_CTOR time() =default
```

Default constructor. Does not initialize the members. 

### function TOML_CONSTRAINED_TEMPLATE

```cpp
TOML_CONSTRAINED_TEMPLATE(
    (impl::all_integral< H, M, S, NS >) ,
    typename H ,
    typename M ,
    typename S  =uint8_t,
    typename NS  =uint32_t
) const
```

Constructs a time from individual time component values. 

### function time

```cpp
TOML_NODISCARD_CTOR time() =default
```


### function TOML_CONSTRAINED_TEMPLATE

```cpp
TOML_CONSTRAINED_TEMPLATE(
    (impl::all_integral< H, M, S, NS >) ,
    typename H ,
    typename M ,
    typename S  =uint8_t,
    typename NS  =uint32_t
) const
```


## Public Attributes Documentation

### variable hour

```cpp
uint8_t hour;
```

The hour component, from 0 - 23. 

### variable minute

```cpp
uint8_t minute;
```

The minute component, from 0 - 59. 

### variable second

```cpp
uint8_t second;
```

The second component, from 0 - 59. 

### variable nanosecond

```cpp
uint32_t nanosecond;
```

The fractional nanoseconds component, from 0 - 999999999. 

### variable m

```cpp
M m;
```


### variable s

```cpp
M S s = S{};
```



_Automatically updated on 2022-05-02 at 01:42:11 +0000._