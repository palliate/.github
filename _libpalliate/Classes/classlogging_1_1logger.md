---
title: logging::logger

---

# logging::logger






`#include <logger.h>`

## Public Functions

|                | Name           |
| -------------- | -------------- |
| [logger](Classes/classlogging_1_1logger.md) & | **[Instance](Classes/classlogging_1_1logger.md#function-instance)**() |
| void | **[register_thread](Classes/classlogging_1_1logger.md#function-register-thread)**(std::string_view name) |
| | **[logger](Classes/classlogging_1_1logger.md#function-logger)**([logger](Classes/classlogging_1_1logger.md) const & ) =delete |
| void | **[operator=](Classes/classlogging_1_1logger.md#function-operator=)**([logger](Classes/classlogging_1_1logger.md) const & ) =delete |
| | **[~logger](Classes/classlogging_1_1logger.md#function-~logger)**() |
| void | **[register_thread](Classes/classlogging_1_1logger.md#function-register-thread)**(std::thread::id thread_id, std::string_view name) |
| void | **[print](Classes/classlogging_1_1logger.md#function-print)**([message](Classes/structlogging_1_1message.md) & msg) |
| template <class T ,typename... Args\> <br>| **[requires](Classes/classlogging_1_1logger.md#function-requires)**(std::derived_from< T, [endpoint::endpoint](Classes/classlogging_1_1endpoint_1_1endpoint.md) > ) |
| void | **[enable](Classes/classlogging_1_1logger.md#function-enable)**() |
| std::string | **[get_name](Classes/classlogging_1_1logger.md#function-get-name)**(std::thread::id thread_id) |

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| [severity](Namespaces/namespacelogging.md#enum-severity) | **[min_level](Classes/classlogging_1_1logger.md#variable-min-level)**  |

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


-------------------------------

Updated on 2022-04-30 at 06:56:37 +0000