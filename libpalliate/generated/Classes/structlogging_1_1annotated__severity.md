---
title: logging::annotated_severity
parent: Classes
grand_parent: libpalliate
layout: default
---

# logging::annotated_severity






`#include <message.h>`

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[annotated_severity](/libpalliate/generated/Classes/structlogging_1_1annotated__severity#function-annotated-severity)**([severity](/libpalliate/generated/Namespaces/namespacelogging#enum-severity) _level, std::thread::id _thread_id =std::this_thread::get_id(), std::source_location _location =std::source_location::current()) |

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| [severity](/libpalliate/generated/Namespaces/namespacelogging#enum-severity) | **[level](/libpalliate/generated/Classes/structlogging_1_1annotated__severity#variable-level)**  |
| std::thread::id | **[thread_id](/libpalliate/generated/Classes/structlogging_1_1annotated__severity#variable-thread-id)**  |
| std::source_location | **[location](/libpalliate/generated/Classes/structlogging_1_1annotated__severity#variable-location)**  |

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



_Automatically updated on 2022-05-07 at 23:35:51 +0000._