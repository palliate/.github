---
title: logging
parent: Namespaces
grand_parent: libpalliate
layout: default
---

# logging



## Namespaces

| Name           |
| -------------- |
| **[logging::endpoint](/libpalliate/generated/Namespaces/namespacelogging_1_1endpoint)**  |

## Classes

|                | Name           |
| -------------- | -------------- |
| struct | **[logging::annotated_severity](/libpalliate/generated/Classes/structlogging_1_1annotated__severity)**  |
| class | **[logging::logger](/libpalliate/generated/Classes/classlogging_1_1logger)**  |
| struct | **[logging::message](/libpalliate/generated/Classes/structlogging_1_1message)**  |

## Types

|                | Name           |
| -------------- | -------------- |
| enum uint8_t | **[severity](/libpalliate/generated/Namespaces/namespacelogging#enum-severity)** { debug = 0, info = 1, warning = 2, error = 3, fatal = 4} |

## Functions

|                | Name           |
| -------------- | -------------- |
| template <typename... Ts\> <br>void | **[print](/libpalliate/generated/Namespaces/namespacelogging#function-print)**([annotated_severity](/libpalliate/generated/Classes/structlogging_1_1annotated__severity) meta, Ts &&... ts) |

## Types Documentation

### enum severity

| Enumerator | Value | Description |
| ---------- | ----- | ----------- |
| debug | 0|   |
| info | 1|   |
| warning | 2|   |
| error | 3|   |
| fatal | 4|   |





## Functions Documentation

### function print

```cpp
template <typename... Ts>
void print(
    annotated_severity meta,
    Ts &&... ts
)
```







_Automatically updated on 2022-05-07 at 23:14:50 +0000._