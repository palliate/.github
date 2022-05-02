---
title: parse_result::storage_t
parent: Classes
grand_parent: libpalliate
layout: default
---

# parse_result::storage_t





## Public Attributes

|                | Name           |
| -------------- | -------------- |
| constexpr size_t | **[size_](/libpalliate/generated/Classes/structparse__result_1_1storage__t#variable-size-)**  |
| constexpr size_t | **[align_](/libpalliate/generated/Classes/structparse__result_1_1storage__t#variable-align-)**  |
| unsigned char | **[bytes](/libpalliate/generated/Classes/structparse__result_1_1storage__t#variable-bytes)**  |

## Public Attributes Documentation

### variable size_

```cpp
static constexpr size_t size_ =
				(sizeof(toml::table) < sizeof(parse_error) ? sizeof(parse_error) : sizeof(toml::table));
```


### variable align_

```cpp
static constexpr size_t align_ =
				(alignof(toml::table) < alignof(parse_error) ? alignof(parse_error) : alignof(toml::table));
```


### variable bytes

```cpp
unsigned char bytes;
```



_Automatically updated on 2022-05-02 at 01:42:07 +0000._