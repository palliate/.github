---
title: util

---

# util



## Namespaces

| Name           |
| -------------- |
| **[util::uuid](Namespaces/namespaceutil_1_1uuid.md)**  |

## Classes

|                | Name           |
| -------------- | -------------- |
| struct | **[util::rect](Classes/structutil_1_1rect.md)**  |

## Functions

|                | Name           |
| -------------- | -------------- |
| uint64_t | **[timestamp](Namespaces/namespaceutil.md#function-timestamp)**() |
| void | **[sleep_for](Namespaces/namespaceutil.md#function-sleep-for)**(auto duration) |
| template <typename T ,bool desired,unsigned sleeptime =0,unsigned timeout =0\> <br>T | **[wait](Namespaces/namespaceutil.md#function-wait)**(std::atomic< T > * p, T value) |
| template <typename T ,unsigned sleeptime =0,unsigned timeout =0\> <br>T | **[wait_undesired](Namespaces/namespaceutil.md#function-wait-undesired)**(std::atomic< T > * p, T undesired) |
| template <typename T ,unsigned sleeptime =0,unsigned timeout =0\> <br>T | **[wait_desired](Namespaces/namespaceutil.md#function-wait-desired)**(std::atomic< T > * p, T desired) |
| std::string_view | **[remove_file_extension](Namespaces/namespaceutil.md#function-remove-file-extension)**(std::string_view file) |
| std::string_view | **[basename](Namespaces/namespaceutil.md#function-basename)**(std::string_view path) |
| std::string_view | **[remove_basedir](Namespaces/namespaceutil.md#function-remove-basedir)**(std::string_view path) |
| std::filesystem::path | **[binary_dir](Namespaces/namespaceutil.md#function-binary-dir)**() |
| std::filesystem::path | **[config_dir](Namespaces/namespaceutil.md#function-config-dir)**() |
| bool | **[iequal](Namespaces/namespaceutil.md#function-iequal)**(std::string_view lhs, std::string_view rhs) |
| bool | **[to_bool](Namespaces/namespaceutil.md#function-to-bool)**(std::string_view str) |
| int | **[to_int](Namespaces/namespaceutil.md#function-to-int)**(std::string_view str) |
| template <typename K ,typename V \> <br>| **[requires](Namespaces/namespaceutil.md#function-requires)**(std::same_as< K, std::string >||std::same_as< K, std::string_view > ) |
| template <typename T \> <br>| **[requires](Namespaces/namespaceutil.md#function-requires)**(std::integral< T > ) |

## Attributes

|                | Name           |
| -------------- | -------------- |
| constexpr static std::string_view | **[library_extension](Namespaces/namespaceutil.md#variable-library-extension)**  |


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





-------------------------------

Updated on 2022-04-30 at 06:56:37 +0000