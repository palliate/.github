---
title: logging::message
parent: Classes
grand_parent: libpalliate
layout: default
---

# logging::message






`#include <message.h>`

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| const [severity](/libpalliate/generated/Namespaces/namespacelogging#enum-severity) | **[level](/libpalliate/generated/Classes/structlogging_1_1message#variable-level)**  |
| const std::thread::id | **[thread_id](/libpalliate/generated/Classes/structlogging_1_1message#variable-thread-id)**  |
| const std::string | **[thread_name](/libpalliate/generated/Classes/structlogging_1_1message#variable-thread-name)**  |
| const std::source_location | **[location](/libpalliate/generated/Classes/structlogging_1_1message#variable-location)**  |
| const std::string | **[text](/libpalliate/generated/Classes/structlogging_1_1message#variable-text)**  |

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



_Automatically updated on 2022-05-07 at 23:35:51 +0000._