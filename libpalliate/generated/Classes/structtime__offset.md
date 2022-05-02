---
title: time_offset
summary: A timezone offset. 
parent: Classes
grand_parent: libpalliate
layout: default
---

# time_offset



A timezone offset. 


`#include <toml.hpp>`

## Public Functions

|                | Name           |
| -------------- | -------------- |
| [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor) | **[time_offset](/libpalliate/generated/Classes/structtime__offset#function-time-offset)**() =default<br>Default constructor. Does not initialize the members.  |
| constexpr [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor) | **[time_offset](/libpalliate/generated/Classes/structtime__offset#function-time-offset)**(H h, M m)<br>Constructs a timezone offset from individual hour and minute totals.  |
| [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor) | **[time_offset](/libpalliate/generated/Classes/structtime__offset#function-time-offset)**() =default |
| constexpr [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor) | **[time_offset](/libpalliate/generated/Classes/structtime__offset#function-time-offset)**(H h, M m) |

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| int16_t | **[minutes](/libpalliate/generated/Classes/structtime__offset#variable-minutes)** <br>Offset from UTC+0, in minutes.  |

## Friends

|                | Name           |
| -------------- | -------------- |
| [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter) constexpr friend bool | **[operator==](/libpalliate/generated/Classes/structtime__offset#friend-operator==)**([time_offset](/libpalliate/generated/Classes/structtime__offset) lhs, [time_offset](/libpalliate/generated/Classes/structtime__offset) rhs) <br>Equality operator.  |
| [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter) constexpr friend bool | **[operator!=](/libpalliate/generated/Classes/structtime__offset#friend-operator!=)**([time_offset](/libpalliate/generated/Classes/structtime__offset) lhs, [time_offset](/libpalliate/generated/Classes/structtime__offset) rhs) <br>Inequality operator.  |
| [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter) constexpr friend bool | **[operator<](/libpalliate/generated/Classes/structtime__offset#friend-operator<)**([time_offset](/libpalliate/generated/Classes/structtime__offset) lhs, [time_offset](/libpalliate/generated/Classes/structtime__offset) rhs) <br>Less-than operator.  |
| [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter) constexpr friend bool | **[operator<=](/libpalliate/generated/Classes/structtime__offset#friend-operator<=)**([time_offset](/libpalliate/generated/Classes/structtime__offset) lhs, [time_offset](/libpalliate/generated/Classes/structtime__offset) rhs) <br>Less-than-or-equal-to operator.  |
| [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter) constexpr friend bool | **[operator>](/libpalliate/generated/Classes/structtime__offset#friend-operator>)**([time_offset](/libpalliate/generated/Classes/structtime__offset) lhs, [time_offset](/libpalliate/generated/Classes/structtime__offset) rhs) <br>Greater-than operator.  |
| [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter) constexpr friend bool | **[operator>=](/libpalliate/generated/Classes/structtime__offset#friend-operator>=)**([time_offset](/libpalliate/generated/Classes/structtime__offset) lhs, [time_offset](/libpalliate/generated/Classes/structtime__offset) rhs) <br>Greater-than-or-equal-to operator.  |
| std::ostream & | **[operator<<](/libpalliate/generated/Classes/structtime__offset#friend-operator<<)**(std::ostream & lhs, const [time_offset](/libpalliate/generated/Classes/structtime__offset) & rhs) <br>Prints a [time_offset](/libpalliate/generated/Classes/structtime__offset) out to a stream as `+-HH:MM or Z` (per RFC 3339). \detail \cpp std::cout << toml::time_offset{ 2, 30 } << "\n"; std::cout << toml::time_offset{ 2, -30 } << "\n"; std::cout << toml::time_offset{} << "\n"; std::cout << toml::time_offset{ -2, 30 } << "\n"; std::cout << toml::time_offset{ -2, -30 } << "\n"; \ecpp.  |
| [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter) constexpr friend bool | **[operator==](/libpalliate/generated/Classes/structtime__offset#friend-operator==)**([time_offset](/libpalliate/generated/Classes/structtime__offset) lhs, [time_offset](/libpalliate/generated/Classes/structtime__offset) rhs)  |
| [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter) constexpr friend bool | **[operator!=](/libpalliate/generated/Classes/structtime__offset#friend-operator!=)**([time_offset](/libpalliate/generated/Classes/structtime__offset) lhs, [time_offset](/libpalliate/generated/Classes/structtime__offset) rhs)  |
| [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter) constexpr friend bool | **[operator<](/libpalliate/generated/Classes/structtime__offset#friend-operator<)**([time_offset](/libpalliate/generated/Classes/structtime__offset) lhs, [time_offset](/libpalliate/generated/Classes/structtime__offset) rhs)  |
| [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter) constexpr friend bool | **[operator<=](/libpalliate/generated/Classes/structtime__offset#friend-operator<=)**([time_offset](/libpalliate/generated/Classes/structtime__offset) lhs, [time_offset](/libpalliate/generated/Classes/structtime__offset) rhs)  |
| [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter) constexpr friend bool | **[operator>](/libpalliate/generated/Classes/structtime__offset#friend-operator>)**([time_offset](/libpalliate/generated/Classes/structtime__offset) lhs, [time_offset](/libpalliate/generated/Classes/structtime__offset) rhs)  |
| [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter) constexpr friend bool | **[operator>=](/libpalliate/generated/Classes/structtime__offset#friend-operator>=)**([time_offset](/libpalliate/generated/Classes/structtime__offset) lhs, [time_offset](/libpalliate/generated/Classes/structtime__offset) rhs)  |
| std::ostream & | **[operator<<](/libpalliate/generated/Classes/structtime__offset#friend-operator<<)**(std::ostream & lhs, const [time_offset](/libpalliate/generated/Classes/structtime__offset) & rhs)  |

## Public Functions Documentation

### function time_offset

```cpp
TOML_NODISCARD_CTOR time_offset() =default
```

Default constructor. Does not initialize the members. 

### function time_offset

```cpp
inline constexpr TOML_NODISCARD_CTOR time_offset(
    H h,
    M m
)
```

Constructs a timezone offset from individual hour and minute totals. 

**Parameters**: 

  * **h** The total hours. 
  * **m** The total minutes. 


**Template Parameters**: 

  * **H** An integral type. 
  * **M** An integral type.


\detail \cpp std::cout << toml::time_offset{ 2, 30 } << "\n"; std::cout << toml::time_offset{ -2, 30 } << "\n"; std::cout << toml::time_offset{ -2, -30 } << "\n"; std::cout << toml::time_offset{ 0, 0 } << "\n"; \ecpp

\out +02:30 -01:30 -02:30 Z \eout


### function time_offset

```cpp
TOML_NODISCARD_CTOR time_offset() =default
```


### function time_offset

```cpp
inline constexpr TOML_NODISCARD_CTOR time_offset(
    H h,
    M m
)
```


**Parameters**: 

  * **h** The total hours. 
  * **m** The total minutes. 


**Template Parameters**: 

  * **H** An integral type. 
  * **M** An integral type.


\detail \cpp std::cout << toml::time_offset{ 2, 30 } << "\n"; std::cout << toml::time_offset{ -2, 30 } << "\n"; std::cout << toml::time_offset{ -2, -30 } << "\n"; std::cout << toml::time_offset{ 0, 0 } << "\n"; \ecpp

\out +02:30 -01:30 -02:30 Z \eout


## Public Attributes Documentation

### variable minutes

```cpp
int16_t minutes;
```

Offset from UTC+0, in minutes. 

## Friends

### friend operator==

```cpp
friend TOML_PURE_GETTER constexpr friend bool operator==(
    time_offset lhs,

    time_offset rhs
);
```

Equality operator. 

### friend operator!=

```cpp
friend TOML_PURE_GETTER constexpr friend bool operator!=(
    time_offset lhs,

    time_offset rhs
);
```

Inequality operator. 

### friend operator<

```cpp
friend TOML_PURE_GETTER constexpr friend bool operator<(
    time_offset lhs,

    time_offset rhs
);
```

Less-than operator. 

### friend operator<=

```cpp
friend TOML_PURE_GETTER constexpr friend bool operator<=(
    time_offset lhs,

    time_offset rhs
);
```

Less-than-or-equal-to operator. 

### friend operator>

```cpp
friend TOML_PURE_GETTER constexpr friend bool operator>(
    time_offset lhs,

    time_offset rhs
);
```

Greater-than operator. 

### friend operator>=

```cpp
friend TOML_PURE_GETTER constexpr friend bool operator>=(
    time_offset lhs,

    time_offset rhs
);
```

Greater-than-or-equal-to operator. 

### friend operator<<

```cpp
friend std::ostream & operator<<(
    std::ostream & lhs,

    const time_offset & rhs
);
```

Prints a [time_offset](/libpalliate/generated/Classes/structtime__offset) out to a stream as `+-HH:MM or Z` (per RFC 3339). \detail \cpp std::cout << toml::time_offset{ 2, 30 } << "\n"; std::cout << toml::time_offset{ 2, -30 } << "\n"; std::cout << toml::time_offset{} << "\n"; std::cout << toml::time_offset{ -2, 30 } << "\n"; std::cout << toml::time_offset{ -2, -30 } << "\n"; \ecpp. 

\out +02:30 +01:30 Z -01:30 -02:30 \eout 


### friend operator==

```cpp
friend TOML_PURE_GETTER constexpr friend bool operator==(
    time_offset lhs,

    time_offset rhs
);
```


### friend operator!=

```cpp
friend TOML_PURE_GETTER constexpr friend bool operator!=(
    time_offset lhs,

    time_offset rhs
);
```


### friend operator<

```cpp
friend TOML_PURE_GETTER constexpr friend bool operator<(
    time_offset lhs,

    time_offset rhs
);
```


### friend operator<=

```cpp
friend TOML_PURE_GETTER constexpr friend bool operator<=(
    time_offset lhs,

    time_offset rhs
);
```


### friend operator>

```cpp
friend TOML_PURE_GETTER constexpr friend bool operator>(
    time_offset lhs,

    time_offset rhs
);
```


### friend operator>=

```cpp
friend TOML_PURE_GETTER constexpr friend bool operator>=(
    time_offset lhs,

    time_offset rhs
);
```


### friend operator<<

```cpp
friend std::ostream & operator<<(
    std::ostream & lhs,

    const time_offset & rhs
);
```


\out +02:30 +01:30 Z -01:30 -02:30 \eout 



_Automatically updated on 2022-05-02 at 01:42:07 +0000._