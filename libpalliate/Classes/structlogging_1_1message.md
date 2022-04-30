---
title: logging::message

---

# logging::message






`#include <message.h>`

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| const [severity](Namespaces/namespacelogging.md#enum-severity) | **[level](Classes/structlogging_1_1message.md#variable-level)**  |
| const std::thread::id | **[thread_id](Classes/structlogging_1_1message.md#variable-thread-id)**  |
| const std::string | **[thread_name](Classes/structlogging_1_1message.md#variable-thread-name)**  |
| const std::source_location | **[location](Classes/structlogging_1_1message.md#variable-location)**  |
| const std::string | **[text](Classes/structlogging_1_1message.md#variable-text)**  |

## Public Attributes Documentation

### variable level

```cpp
const severity level;
```


### variable thread_id

```cpp
const std::thread::id thread_id;
```


### variable thread_name

```cpp
const std::string thread_name;
```


### variable location

```cpp
const std::source_location location;
```


### variable text

```cpp
const std::string text;
```


-------------------------------

Updated on 2022-04-30 at 06:56:37 +0000