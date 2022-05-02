---
title: element
parent: Classes
grand_parent: libpalliate
layout: default
---

# element






`#include <atomic_semaphore.h>`

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| std::atomic< unsigned long long > | **[expiration_time](/libpalliate/generated/Classes/structelement#variable-expiration-time)**  |
| std::atomic< unsigned > | **[req](/libpalliate/generated/Classes/structelement#variable-req)**  |
| std::atomic< unsigned > | **[resp](/libpalliate/generated/Classes/structelement#variable-resp)**  |
| std::atomic_flag | **[processed](/libpalliate/generated/Classes/structelement#variable-processed)**  |
| std::atomic< unsigned > | **[flag](/libpalliate/generated/Classes/structelement#variable-flag)**  |
| unsigned | **[max](/libpalliate/generated/Classes/structelement#variable-max)**  |
| uint64_t | **[expiration_time](/libpalliate/generated/Classes/structelement#variable-expiration-time)**  |
| unsigned | **[data](/libpalliate/generated/Classes/structelement#variable-data)**  |

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



_Automatically updated on 2022-05-02 at 01:49:09 +0000._