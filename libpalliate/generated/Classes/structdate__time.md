---
title: date_time
summary: A date-time. 
parent: Classes
grand_parent: libpalliate
layout: default
---

# date_time



A date-time. 


`#include <toml.hpp>`

## Public Functions

|                | Name           |
| -------------- | -------------- |
| [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor) | **[date_time](/libpalliate/generated/Classes/structdate__time#function-date-time)**() =default<br>Default constructor. Does not initialize the members.  |
| constexpr [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor) | **[date_time](/libpalliate/generated/Classes/structdate__time#function-date-time)**(const toml::date & d, const toml::time & t)<br>Constructs a local date-time.  |
| constexpr [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor) | **[date_time](/libpalliate/generated/Classes/structdate__time#function-date-time)**(const toml::date & d)<br>Constructs a local date-time.  |
| constexpr [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor) | **[date_time](/libpalliate/generated/Classes/structdate__time#function-date-time)**(const toml::time & t)<br>Constructs a local date-time.  |
| constexpr [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor) | **[date_time](/libpalliate/generated/Classes/structdate__time#function-date-time)**(const toml::date & d, const toml::time & t, const toml::time_offset & off)<br>Constructs an offset date-time.  |
| constexpr [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter) bool | **[is_local](/libpalliate/generated/Classes/structdate__time#function-is-local)**() const<br>Returns true if this [date_time](/libpalliate/generated/Classes/structdate__time) does not contain timezone offset information.  |
| [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor) | **[date_time](/libpalliate/generated/Classes/structdate__time#function-date-time)**() =default |
| constexpr [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor) | **[date_time](/libpalliate/generated/Classes/structdate__time#function-date-time)**(const toml::date & d, const toml::time & t) |
| constexpr [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor) | **[date_time](/libpalliate/generated/Classes/structdate__time#function-date-time)**(const toml::date & d) |
| constexpr [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor) | **[date_time](/libpalliate/generated/Classes/structdate__time#function-date-time)**(const toml::time & t) |
| constexpr [TOML_NODISCARD_CTOR](/libpalliate/generated/Files/toml_8hpp#define-toml-nodiscard-ctor) | **[date_time](/libpalliate/generated/Classes/structdate__time#function-date-time)**(const toml::date & d, const toml::time & t, const toml::time_offset & off) |
| constexpr [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter) bool | **[is_local](/libpalliate/generated/Classes/structdate__time#function-is-local)**() const |

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| toml::date | **[date](/libpalliate/generated/Classes/structdate__time#variable-date)** <br>The date component.  |
| toml::time | **[time](/libpalliate/generated/Classes/structdate__time#variable-time)** <br>The time component.  |
| optional< toml::time_offset > | **[offset](/libpalliate/generated/Classes/structdate__time#variable-offset)** <br>The timezone offset component.  |

## Friends

|                | Name           |
| -------------- | -------------- |
| [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter) constexpr friend bool | **[operator==](/libpalliate/generated/Classes/structdate__time#friend-operator==)**(const [date_time](/libpalliate/generated/Classes/structdate__time) & lhs, const [date_time](/libpalliate/generated/Classes/structdate__time) & rhs) <br>Equality operator.  |
| [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter) constexpr friend bool | **[operator!=](/libpalliate/generated/Classes/structdate__time#friend-operator!=)**(const [date_time](/libpalliate/generated/Classes/structdate__time) & lhs, const [date_time](/libpalliate/generated/Classes/structdate__time) & rhs) <br>Inequality operator.  |
| [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter) constexpr friend bool | **[operator<](/libpalliate/generated/Classes/structdate__time#friend-operator<)**(const [date_time](/libpalliate/generated/Classes/structdate__time) & lhs, const [date_time](/libpalliate/generated/Classes/structdate__time) & rhs) <br>Less-than operator.  |
| [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter) constexpr friend bool | **[operator<=](/libpalliate/generated/Classes/structdate__time#friend-operator<=)**(const [date_time](/libpalliate/generated/Classes/structdate__time) & lhs, const [date_time](/libpalliate/generated/Classes/structdate__time) & rhs) <br>Less-than-or-equal-to operator.  |
| [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter) constexpr friend bool | **[operator>](/libpalliate/generated/Classes/structdate__time#friend-operator>)**(const [date_time](/libpalliate/generated/Classes/structdate__time) & lhs, const [date_time](/libpalliate/generated/Classes/structdate__time) & rhs) <br>Greater-than operator.  |
| [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter) constexpr friend bool | **[operator>=](/libpalliate/generated/Classes/structdate__time#friend-operator>=)**(const [date_time](/libpalliate/generated/Classes/structdate__time) & lhs, const [date_time](/libpalliate/generated/Classes/structdate__time) & rhs) <br>Greater-than-or-equal-to operator.  |
| std::ostream & | **[operator<<](/libpalliate/generated/Classes/structdate__time#friend-operator<<)**(std::ostream & lhs, const [date_time](/libpalliate/generated/Classes/structdate__time) & rhs) <br>Prints a [date_time](/libpalliate/generated/Classes/structdate__time) out to a stream in RFC 3339 format. \detail \cpp std::cout << toml::date_time{ { 1987, 3, 16 }, { 10, 20, 34 } } << "\n"; std::cout << toml::date_time{ { 1987, 3, 16 }, { 10, 20, 34 }, { -2, -30 } } << "\n"; std::cout << toml::date_time{ { 1987, 3, 16 }, { 10, 20, 34 }, {} } << "\n"; \ecpp.  |
| [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter) constexpr friend bool | **[operator==](/libpalliate/generated/Classes/structdate__time#friend-operator==)**(const [date_time](/libpalliate/generated/Classes/structdate__time) & lhs, const [date_time](/libpalliate/generated/Classes/structdate__time) & rhs)  |
| [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter) constexpr friend bool | **[operator!=](/libpalliate/generated/Classes/structdate__time#friend-operator!=)**(const [date_time](/libpalliate/generated/Classes/structdate__time) & lhs, const [date_time](/libpalliate/generated/Classes/structdate__time) & rhs)  |
| [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter) constexpr friend bool | **[operator<](/libpalliate/generated/Classes/structdate__time#friend-operator<)**(const [date_time](/libpalliate/generated/Classes/structdate__time) & lhs, const [date_time](/libpalliate/generated/Classes/structdate__time) & rhs)  |
| [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter) constexpr friend bool | **[operator<=](/libpalliate/generated/Classes/structdate__time#friend-operator<=)**(const [date_time](/libpalliate/generated/Classes/structdate__time) & lhs, const [date_time](/libpalliate/generated/Classes/structdate__time) & rhs)  |
| [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter) constexpr friend bool | **[operator>](/libpalliate/generated/Classes/structdate__time#friend-operator>)**(const [date_time](/libpalliate/generated/Classes/structdate__time) & lhs, const [date_time](/libpalliate/generated/Classes/structdate__time) & rhs)  |
| [TOML_PURE_GETTER](/libpalliate/generated/Files/toml_8hpp#define-toml-pure-getter) constexpr friend bool | **[operator>=](/libpalliate/generated/Classes/structdate__time#friend-operator>=)**(const [date_time](/libpalliate/generated/Classes/structdate__time) & lhs, const [date_time](/libpalliate/generated/Classes/structdate__time) & rhs)  |
| std::ostream & | **[operator<<](/libpalliate/generated/Classes/structdate__time#friend-operator<<)**(std::ostream & lhs, const [date_time](/libpalliate/generated/Classes/structdate__time) & rhs)  |

## Public Functions Documentation

### function date_time

```cpp
TOML_NODISCARD_CTOR date_time() =default
```

Default constructor. Does not initialize the members. 

### function date_time

```cpp
inline constexpr TOML_NODISCARD_CTOR date_time(
    const toml::date & d,
    const toml::time & t
)
```

Constructs a local date-time. 

**Parameters**: 

  * **d** The date component. 
  * **t** The time component. 


### function date_time

```cpp
inline explicit constexpr TOML_NODISCARD_CTOR date_time(
    const toml::date & d
)
```

Constructs a local date-time. 

**Parameters**: 

  * **d** The date component. 


### function date_time

```cpp
inline explicit constexpr TOML_NODISCARD_CTOR date_time(
    const toml::time & t
)
```

Constructs a local date-time. 

**Parameters**: 

  * **t** The time component. 


### function date_time

```cpp
inline constexpr TOML_NODISCARD_CTOR date_time(
    const toml::date & d,
    const toml::time & t,
    const toml::time_offset & off
)
```

Constructs an offset date-time. 

**Parameters**: 

  * **d** The date component. 
  * **t** The time component. 
  * **off** The timezone offset. 


### function is_local

```cpp
inline constexpr TOML_PURE_GETTER bool is_local() const
```

Returns true if this [date_time](/libpalliate/generated/Classes/structdate__time) does not contain timezone offset information. 

### function date_time

```cpp
TOML_NODISCARD_CTOR date_time() =default
```


### function date_time

```cpp
inline constexpr TOML_NODISCARD_CTOR date_time(
    const toml::date & d,
    const toml::time & t
)
```


**Parameters**: 

  * **d** The date component. 
  * **t** The time component. 


### function date_time

```cpp
inline explicit constexpr TOML_NODISCARD_CTOR date_time(
    const toml::date & d
)
```


**Parameters**: 

  * **d** The date component. 


### function date_time

```cpp
inline explicit constexpr TOML_NODISCARD_CTOR date_time(
    const toml::time & t
)
```


**Parameters**: 

  * **t** The time component. 


### function date_time

```cpp
inline constexpr TOML_NODISCARD_CTOR date_time(
    const toml::date & d,
    const toml::time & t,
    const toml::time_offset & off
)
```


**Parameters**: 

  * **d** The date component. 
  * **t** The time component. 
  * **off** The timezone offset. 


### function is_local

```cpp
inline constexpr TOML_PURE_GETTER bool is_local() const
```


## Public Attributes Documentation

### variable date

```cpp
toml::date date;
```

The date component. 

### variable time

```cpp
toml::time time;
```

The time component. 

### variable offset

```cpp
optional< toml::time_offset > offset;
```

The timezone offset component. 

**Remark**: The [date_time](/libpalliate/generated/Classes/structdate__time) is said to be 'local' if the offset is empty. 

## Friends

### friend operator==

```cpp
friend TOML_PURE_GETTER constexpr friend bool operator==(
    const date_time & lhs,

    const date_time & rhs
);
```

Equality operator. 

### friend operator!=

```cpp
friend TOML_PURE_GETTER constexpr friend bool operator!=(
    const date_time & lhs,

    const date_time & rhs
);
```

Inequality operator. 

### friend operator<

```cpp
friend TOML_PURE_GETTER constexpr friend bool operator<(
    const date_time & lhs,

    const date_time & rhs
);
```

Less-than operator. 

### friend operator<=

```cpp
friend TOML_PURE_GETTER constexpr friend bool operator<=(
    const date_time & lhs,

    const date_time & rhs
);
```

Less-than-or-equal-to operator. 

### friend operator>

```cpp
friend TOML_PURE_GETTER constexpr friend bool operator>(
    const date_time & lhs,

    const date_time & rhs
);
```

Greater-than operator. 

### friend operator>=

```cpp
friend TOML_PURE_GETTER constexpr friend bool operator>=(
    const date_time & lhs,

    const date_time & rhs
);
```

Greater-than-or-equal-to operator. 

### friend operator<<

```cpp
friend std::ostream & operator<<(
    std::ostream & lhs,

    const date_time & rhs
);
```

Prints a [date_time](/libpalliate/generated/Classes/structdate__time) out to a stream in RFC 3339 format. \detail \cpp std::cout << toml::date_time{ { 1987, 3, 16 }, { 10, 20, 34 } } << "\n"; std::cout << toml::date_time{ { 1987, 3, 16 }, { 10, 20, 34 }, { -2, -30 } } << "\n"; std::cout << toml::date_time{ { 1987, 3, 16 }, { 10, 20, 34 }, {} } << "\n"; \ecpp. 

\out 1987-03-16T10:20:34 1987-03-16T10:20:34-02:30 1987-03-16T10:20:34Z \eout 


### friend operator==

```cpp
friend TOML_PURE_GETTER constexpr friend bool operator==(
    const date_time & lhs,

    const date_time & rhs
);
```


### friend operator!=

```cpp
friend TOML_PURE_GETTER constexpr friend bool operator!=(
    const date_time & lhs,

    const date_time & rhs
);
```


### friend operator<

```cpp
friend TOML_PURE_GETTER constexpr friend bool operator<(
    const date_time & lhs,

    const date_time & rhs
);
```


### friend operator<=

```cpp
friend TOML_PURE_GETTER constexpr friend bool operator<=(
    const date_time & lhs,

    const date_time & rhs
);
```


### friend operator>

```cpp
friend TOML_PURE_GETTER constexpr friend bool operator>(
    const date_time & lhs,

    const date_time & rhs
);
```


### friend operator>=

```cpp
friend TOML_PURE_GETTER constexpr friend bool operator>=(
    const date_time & lhs,

    const date_time & rhs
);
```


### friend operator<<

```cpp
friend std::ostream & operator<<(
    std::ostream & lhs,

    const date_time & rhs
);
```


\out 1987-03-16T10:20:34 1987-03-16T10:20:34-02:30 1987-03-16T10:20:34Z \eout 



_Automatically updated on 2022-05-02 at 01:42:11 +0000._