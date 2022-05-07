---
title: logging::endpoint::endpoint
parent: Classes
grand_parent: libpalliate
layout: default
---

# logging::endpoint::endpoint






`#include <endpoint.h>`

Inherited by [logging::endpoint::file](/libpalliate/generated/Classes/classlogging_1_1endpoint_1_1file), [logging::endpoint::systemd](/libpalliate/generated/Classes/classlogging_1_1endpoint_1_1systemd), [logging::endpoint::terminal](/libpalliate/generated/Classes/classlogging_1_1endpoint_1_1terminal)

## Public Functions

|                | Name           |
| -------------- | -------------- |
| virtual | **[~endpoint](/libpalliate/generated/Classes/classlogging_1_1endpoint_1_1endpoint#function-~endpoint)**() |
| virtual void | **[print](/libpalliate/generated/Classes/classlogging_1_1endpoint_1_1endpoint#function-print)**([message](/libpalliate/generated/Classes/structlogging_1_1message) & msg) =0 |

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


**Reimplemented by**: [logging::endpoint::terminal::print](/libpalliate/generated/Classes/classlogging_1_1endpoint_1_1terminal#function-print), [logging::endpoint::systemd::print](/libpalliate/generated/Classes/classlogging_1_1endpoint_1_1systemd#function-print), [logging::endpoint::file::print](/libpalliate/generated/Classes/classlogging_1_1endpoint_1_1file#function-print)



_Automatically updated on 2022-05-07 at 23:14:50 +0000._