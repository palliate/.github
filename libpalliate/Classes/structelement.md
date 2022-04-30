---
title: element

---

# element






`#include <atomic_semaphore.h>`

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| std::atomic< unsigned long long > | **[expiration_time](Classes/structelement.md#variable-expiration-time)**  |
| std::atomic< unsigned > | **[req](Classes/structelement.md#variable-req)**  |
| std::atomic< unsigned > | **[resp](Classes/structelement.md#variable-resp)**  |
| std::atomic_flag | **[processed](Classes/structelement.md#variable-processed)**  |
| std::atomic< unsigned > | **[flag](Classes/structelement.md#variable-flag)**  |
| unsigned | **[max](Classes/structelement.md#variable-max)**  |
| uint64_t | **[expiration_time](Classes/structelement.md#variable-expiration-time)**  |
| unsigned | **[data](Classes/structelement.md#variable-data)**  |

## Public Attributes Documentation

### variable expiration_time

```cpp
std::atomic< unsigned long long > expiration_time = 0;
```


### variable req

```cpp
std::atomic< unsigned > req;
```


### variable resp

```cpp
std::atomic< unsigned > resp;
```


### variable processed

```cpp
std::atomic_flag processed = ATOMIC_FLAG_INIT;
```


### variable flag

```cpp
std::atomic< unsigned > flag {0};
```


### variable max

```cpp
unsigned max = 0;
```


### variable expiration_time

```cpp
uint64_t expiration_time = 0;
```


### variable data

```cpp
unsigned data;
```


-------------------------------

Updated on 2022-04-30 at 06:56:37 +0000