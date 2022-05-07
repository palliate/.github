---
title: logging::endpoint::file
parent: Classes
grand_parent: libpalliate
layout: default
---

# logging::endpoint::file






`#include <file.h>`

Inherits from [logging::endpoint::endpoint](/libpalliate/generated/Classes/classlogging_1_1endpoint_1_1endpoint)

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[file](/libpalliate/generated/Classes/classlogging_1_1endpoint_1_1file#function-file)**(const std::string & path, const std::string & _file_ending =".log"s) |
| | **[file](/libpalliate/generated/Classes/classlogging_1_1endpoint_1_1file#function-file)**(std::filesystem::path outdir, const std::string & _file_ending =".log"s) |
| | **[file](/libpalliate/generated/Classes/classlogging_1_1endpoint_1_1file#function-file)**() |
| virtual void | **[print](/libpalliate/generated/Classes/classlogging_1_1endpoint_1_1file#function-print)**([message](/libpalliate/generated/Classes/structlogging_1_1message) & msg) override |

## Additional inherited members

**Public Functions inherited from [logging::endpoint::endpoint](/libpalliate/generated/Classes/classlogging_1_1endpoint_1_1endpoint)**

|                | Name           |
| -------------- | -------------- |
| virtual | **[~endpoint](/libpalliate/generated/Classes/classlogging_1_1endpoint_1_1endpoint#function-~endpoint)**() |


## Public Functions Documentation

### function file

```cpp
explicit file(
    const std::string & path,
    const std::string & _file_ending =".log"s
)
```


### function file

```cpp
explicit file(
    std::filesystem::path outdir,
    const std::string & _file_ending =".log"s
)
```


### function file

```cpp
inline file()
```


### function print

```cpp
virtual void print(
    message & msg
) override
```


**Reimplements**: [logging::endpoint::endpoint::print](/libpalliate/generated/Classes/classlogging_1_1endpoint_1_1endpoint#function-print)



_Automatically updated on 2022-05-07 at 23:06:39 +0000._