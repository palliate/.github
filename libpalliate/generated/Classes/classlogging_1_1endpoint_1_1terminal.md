---
title: logging::endpoint::terminal
parent: Classes
grand_parent: libpalliate
layout: default
---

# logging::endpoint::terminal






`#include <terminal.h>`

Inherits from [logging::endpoint::endpoint](/libpalliate/generated/Classes/classlogging_1_1endpoint_1_1endpoint)

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[terminal](/libpalliate/generated/Classes/classlogging_1_1endpoint_1_1terminal#function-terminal)**(bool _colored =true) |
| | **[~terminal](/libpalliate/generated/Classes/classlogging_1_1endpoint_1_1terminal#function-~terminal)**() |
| virtual void | **[print](/libpalliate/generated/Classes/classlogging_1_1endpoint_1_1terminal#function-print)**([message](/libpalliate/generated/Classes/structlogging_1_1message) & msg) override |

## Additional inherited members

**Public Functions inherited from [logging::endpoint::endpoint](/libpalliate/generated/Classes/classlogging_1_1endpoint_1_1endpoint)**

|                | Name           |
| -------------- | -------------- |
| virtual | **[~endpoint](/libpalliate/generated/Classes/classlogging_1_1endpoint_1_1endpoint#function-~endpoint)**() |


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


**Reimplements**: [logging::endpoint::endpoint::print](/libpalliate/generated/Classes/classlogging_1_1endpoint_1_1endpoint#function-print)



_Automatically updated on 2022-05-07 at 23:06:39 +0000._