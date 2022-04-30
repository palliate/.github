---
title: logging

---

# logging



## Namespaces

| Name           |
| -------------- |
| **[logging::endpoint](Namespaces/namespacelogging_1_1endpoint.md)**  |

## Classes

|                | Name           |
| -------------- | -------------- |
| struct | **[logging::annotated_severity](Classes/structlogging_1_1annotated__severity.md)**  |
| class | **[logging::logger](Classes/classlogging_1_1logger.md)**  |
| struct | **[logging::message](Classes/structlogging_1_1message.md)**  |

## Types

|                | Name           |
| -------------- | -------------- |
| enum uint8_t | **[severity](Namespaces/namespacelogging.md#enum-severity)** { debug = 0, info = 1, warning = 2, error = 3, fatal = 4} |

## Functions

|                | Name           |
| -------------- | -------------- |
| template <typename... Ts\> <br>void | **[print](Namespaces/namespacelogging.md#function-print)**([annotated_severity](Classes/structlogging_1_1annotated__severity.md) meta, Ts &&... ts) |

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






-------------------------------

Updated on 2022-04-30 at 06:56:37 +0000