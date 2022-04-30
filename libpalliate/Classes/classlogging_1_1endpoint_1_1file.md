---
title: logging::endpoint::file

---

# logging::endpoint::file






`#include <file.h>`

Inherits from [logging::endpoint::endpoint](Classes/classlogging_1_1endpoint_1_1endpoint.md)

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[file](Classes/classlogging_1_1endpoint_1_1file.md#function-file)**(const std::string & path, const std::string & _file_ending =".log"s) |
| | **[file](Classes/classlogging_1_1endpoint_1_1file.md#function-file)**(std::filesystem::path outdir, const std::string & _file_ending =".log"s) |
| | **[file](Classes/classlogging_1_1endpoint_1_1file.md#function-file)**() |
| virtual void | **[print](Classes/classlogging_1_1endpoint_1_1file.md#function-print)**([message](Classes/structlogging_1_1message.md) & msg) override |

## Additional inherited members

**Public Functions inherited from [logging::endpoint::endpoint](Classes/classlogging_1_1endpoint_1_1endpoint.md)**

|                | Name           |
| -------------- | -------------- |
| virtual | **[~endpoint](Classes/classlogging_1_1endpoint_1_1endpoint.md#function-~endpoint)**() |


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


**Reimplements**: [logging::endpoint::endpoint::print](Classes/classlogging_1_1endpoint_1_1endpoint.md#function-print)


-------------------------------

Updated on 2022-04-30 at 06:56:37 +0000