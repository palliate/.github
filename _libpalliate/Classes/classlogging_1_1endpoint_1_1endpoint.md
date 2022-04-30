---
title: logging::endpoint::endpoint

---

# logging::endpoint::endpoint






`#include <endpoint.h>`

Inherited by [logging::endpoint::file](Classes/classlogging_1_1endpoint_1_1file.md), [logging::endpoint::systemd](Classes/classlogging_1_1endpoint_1_1systemd.md), [logging::endpoint::terminal](Classes/classlogging_1_1endpoint_1_1terminal.md)

## Public Functions

|                | Name           |
| -------------- | -------------- |
| virtual | **[~endpoint](Classes/classlogging_1_1endpoint_1_1endpoint.md#function-~endpoint)**() |
| virtual void | **[print](Classes/classlogging_1_1endpoint_1_1endpoint.md#function-print)**([message](Classes/structlogging_1_1message.md) & msg) =0 |

## Public Functions Documentation

### function ~endpoint

```cpp
inline virtual ~endpoint()
```


### function print

```cpp
virtual void print(
    message & msg
) =0
```


**Reimplemented by**: [logging::endpoint::terminal::print](Classes/classlogging_1_1endpoint_1_1terminal.md#function-print), [logging::endpoint::systemd::print](Classes/classlogging_1_1endpoint_1_1systemd.md#function-print), [logging::endpoint::file::print](Classes/classlogging_1_1endpoint_1_1file.md#function-print)


-------------------------------

Updated on 2022-04-30 at 06:56:37 +0000