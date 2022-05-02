---
title: logging::logger
parent: Classes
grand_parent: libpalliate
layout: default
---

# logging::logger






`#include <logger.h>`

## Public Functions

|                | Name           |
| -------------- | -------------- |
| [logger](/libpalliate/generated/Classes/classlogging_1_1logger) & | **[Instance](/libpalliate/generated/Classes/classlogging_1_1logger#function-instance)**() |
| void | **[register_thread](/libpalliate/generated/Classes/classlogging_1_1logger#function-register-thread)**(std::string_view name) |
| | **[logger](/libpalliate/generated/Classes/classlogging_1_1logger#function-logger)**([logger](/libpalliate/generated/Classes/classlogging_1_1logger) const & ) =delete |
| void | **[operator=](/libpalliate/generated/Classes/classlogging_1_1logger#function-operator=)**([logger](/libpalliate/generated/Classes/classlogging_1_1logger) const & ) =delete |
| | **[~logger](/libpalliate/generated/Classes/classlogging_1_1logger#function-~logger)**() |
| void | **[register_thread](/libpalliate/generated/Classes/classlogging_1_1logger#function-register-thread)**(std::thread::id thread_id, std::string_view name) |
| void | **[print](/libpalliate/generated/Classes/classlogging_1_1logger#function-print)**([message](/libpalliate/generated/Classes/structlogging_1_1message) & msg) |
| template <class T ,typename... Args\> <br>| **[requires](/libpalliate/generated/Classes/classlogging_1_1logger#function-requires)**(std::derived_from< T, [endpoint::endpoint](/libpalliate/generated/Classes/classlogging_1_1endpoint_1_1endpoint) > ) |
| void | **[enable](/libpalliate/generated/Classes/classlogging_1_1logger#function-enable)**() |
| std::string | **[get_name](/libpalliate/generated/Classes/classlogging_1_1logger#function-get-name)**(std::thread::id thread_id) |

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| [severity](/libpalliate/generated/Namespaces/namespacelogging#enum-severity) | **[min_level](/libpalliate/generated/Classes/classlogging_1_1logger#variable-min-level)**  |

## Public Functions Documentation

### function Instance

```cpp
static logger & Instance()
```


### function register_thread

```cpp
static void register_thread(
    std::string_view name
)
```


### function logger

```cpp
logger(
    logger const & 
) =delete
```


### function operator=

```cpp
void operator=(
    logger const & 
) =delete
```


### function ~logger

```cpp
~logger()
```


### function register_thread

```cpp
void register_thread(
    std::thread::id thread_id,
    std::string_view name
)
```


### function print

```cpp
void print(
    message & msg
)
```


### function requires

```cpp
template <class T ,
typename... Args>
requires(
    std::derived_from< T, endpoint::endpoint > 
)
```


### function enable

```cpp
void enable()
```


### function get_name

```cpp
std::string get_name(
    std::thread::id thread_id
)
```


## Public Attributes Documentation

### variable min_level

```cpp
severity min_level = severity::warning;
```



_Automatically updated on 2022-05-02 at 01:49:10 +0000._