---
title: logging::annotated_severity

---

# logging::annotated_severity






`#include <message.h>`

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[annotated_severity](Classes/structlogging_1_1annotated__severity.md#function-annotated-severity)**([severity](Namespaces/namespacelogging.md#enum-severity) _level, std::thread::id _thread_id =std::this_thread::get_id(), std::source_location _location =std::source_location::current()) |

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| [severity](Namespaces/namespacelogging.md#enum-severity) | **[level](Classes/structlogging_1_1annotated__severity.md#variable-level)**  |
| std::thread::id | **[thread_id](Classes/structlogging_1_1annotated__severity.md#variable-thread-id)**  |
| std::source_location | **[location](Classes/structlogging_1_1annotated__severity.md#variable-location)**  |

## Public Functions Documentation

### function annotated_severity

```cpp
inline annotated_severity(
    severity _level,
    std::thread::id _thread_id =std::this_thread::get_id(),
    std::source_location _location =std::source_location::current()
)
```


## Public Attributes Documentation

### variable level

```cpp
severity level;
```


### variable thread_id

```cpp
std::thread::id thread_id;
```


### variable location

```cpp
std::source_location location;
```


-------------------------------

Updated on 2022-04-30 at 06:56:37 +0000