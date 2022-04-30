---
title: logging::endpoint::terminal

---

# logging::endpoint::terminal






`#include <terminal.h>`

Inherits from [logging::endpoint::endpoint](Classes/classlogging_1_1endpoint_1_1endpoint.md)

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[terminal](Classes/classlogging_1_1endpoint_1_1terminal.md#function-terminal)**(bool _colored =true) |
| | **[~terminal](Classes/classlogging_1_1endpoint_1_1terminal.md#function-~terminal)**() |
| virtual void | **[print](Classes/classlogging_1_1endpoint_1_1terminal.md#function-print)**([message](Classes/structlogging_1_1message.md) & msg) override |

## Additional inherited members

**Public Functions inherited from [logging::endpoint::endpoint](Classes/classlogging_1_1endpoint_1_1endpoint.md)**

|                | Name           |
| -------------- | -------------- |
| virtual | **[~endpoint](Classes/classlogging_1_1endpoint_1_1endpoint.md#function-~endpoint)**() |


## Public Functions Documentation

### function terminal

```cpp
explicit terminal(
    bool _colored =true
)
```


### function ~terminal

```cpp
~terminal()
```


### function print

```cpp
virtual void print(
    message & msg
) override
```


**Reimplements**: [logging::endpoint::endpoint::print](Classes/classlogging_1_1endpoint_1_1endpoint.md#function-print)


-------------------------------

Updated on 2022-04-30 at 06:56:37 +0000