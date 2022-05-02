---
title: util
parent: Namespaces
grand_parent: libpalliate
layout: default
---

# util



## Namespaces

| Name           |
| -------------- |
| **[util::uuid](/libpalliate/generated/Namespaces/namespaceutil_1_1uuid)**  |

## Classes

|                | Name           |
| -------------- | -------------- |
| struct | **[util::rect](/libpalliate/generated/Classes/structutil_1_1rect)**  |

## Functions

|                | Name           |
| -------------- | -------------- |
| uint64_t | **[timestamp](/libpalliate/generated/Namespaces/namespaceutil#function-timestamp)**() |
| void | **[sleep_for](/libpalliate/generated/Namespaces/namespaceutil#function-sleep-for)**(auto duration) |
| template <typename T ,bool desired,unsigned sleeptime =0,unsigned timeout =0\> <br>T | **[wait](/libpalliate/generated/Namespaces/namespaceutil#function-wait)**(std::atomic< T > * p, T value) |
| template <typename T ,unsigned sleeptime =0,unsigned timeout =0\> <br>T | **[wait_undesired](/libpalliate/generated/Namespaces/namespaceutil#function-wait-undesired)**(std::atomic< T > * p, T undesired) |
| template <typename T ,unsigned sleeptime =0,unsigned timeout =0\> <br>T | **[wait_desired](/libpalliate/generated/Namespaces/namespaceutil#function-wait-desired)**(std::atomic< T > * p, T desired) |
| std::string_view | **[remove_file_extension](/libpalliate/generated/Namespaces/namespaceutil#function-remove-file-extension)**(std::string_view file) |
| std::string_view | **[basename](/libpalliate/generated/Namespaces/namespaceutil#function-basename)**(std::string_view path) |
| std::string_view | **[remove_basedir](/libpalliate/generated/Namespaces/namespaceutil#function-remove-basedir)**(std::string_view path) |
| std::filesystem::path | **[binary_dir](/libpalliate/generated/Namespaces/namespaceutil#function-binary-dir)**() |
| std::filesystem::path | **[config_dir](/libpalliate/generated/Namespaces/namespaceutil#function-config-dir)**() |
| bool | **[iequal](/libpalliate/generated/Namespaces/namespaceutil#function-iequal)**(std::string_view lhs, std::string_view rhs) |
| bool | **[to_bool](/libpalliate/generated/Namespaces/namespaceutil#function-to-bool)**(std::string_view str) |
| int | **[to_int](/libpalliate/generated/Namespaces/namespaceutil#function-to-int)**(std::string_view str) |
| template <typename K ,typename V \> <br>| **[requires](/libpalliate/generated/Namespaces/namespaceutil#function-requires)**(std::same_as< K, std::string >||std::same_as< K, std::string_view > ) |
| template <typename T \> <br>| **[requires](/libpalliate/generated/Namespaces/namespaceutil#function-requires)**(std::integral< T > ) |

## Attributes

|                | Name           |
| -------------- | -------------- |
| constexpr static std::string_view | **[library_extension](/libpalliate/generated/Namespaces/namespaceutil#variable-library-extension)**  |


## Functions Documentation

### function timestamp

```cpp
inline uint64_t timestamp()
```


### function sleep_for

```cpp
inline void sleep_for(
    auto duration
)
```


### function wait

```cpp
template <typename T ,
bool desired,
unsigned sleeptime =0,
unsigned timeout =0>
T wait(
    std::atomic< T > * p,
    T value
)
```


### function wait_undesired

```cpp
template <typename T ,
unsigned sleeptime =0,
unsigned timeout =0>
T wait_undesired(
    std::atomic< T > * p,
    T undesired
)
```


### function wait_desired

```cpp
template <typename T ,
unsigned sleeptime =0,
unsigned timeout =0>
T wait_desired(
    std::atomic< T > * p,
    T desired
)
```


### function remove_file_extension

```cpp
inline std::string_view remove_file_extension(
    std::string_view file
)
```


### function basename

```cpp
inline std::string_view basename(
    std::string_view path
)
```


### function remove_basedir

```cpp
inline std::string_view remove_basedir(
    std::string_view path
)
```


### function binary_dir

```cpp
std::filesystem::path binary_dir()
```


### function config_dir

```cpp
std::filesystem::path config_dir()
```


### function iequal

```cpp
inline bool iequal(
    std::string_view lhs,
    std::string_view rhs
)
```


### function to_bool

```cpp
inline bool to_bool(
    std::string_view str
)
```


### function to_int

```cpp
inline int to_int(
    std::string_view str
)
```


### function requires

```cpp
template <typename K ,
typename V >
requires(
    std::same_as< K, std::string >||std::same_as< K, std::string_view > 
)
```


### function requires

```cpp
template <typename T >
requires(
    std::integral< T > 
)
```



## Attributes Documentation

### variable library_extension

```cpp
static constexpr static std::string_view library_extension = ".so";
```






_Automatically updated on 2022-05-02 at 01:42:07 +0000._