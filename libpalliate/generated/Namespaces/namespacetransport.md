---
title: transport
parent: Namespaces
grand_parent: libpalliate
layout: default
---

# transport



## Namespaces

| Name           |
| -------------- |
| **[transport::tcp](/libpalliate/generated/Namespaces/namespacetransport_1_1tcp)**  |

## Classes

|                | Name           |
| -------------- | -------------- |
| class | **[transport::client](/libpalliate/generated/Classes/classtransport_1_1client)**  |
| class | **[transport::server](/libpalliate/generated/Classes/classtransport_1_1server)**  |

## Types

|                | Name           |
| -------------- | -------------- |
| using std::unique_ptr<::capnp::MessageReader > | **[reader_t](/libpalliate/generated/Namespaces/namespacetransport#using-reader-t)**  |
| using std::unique_ptr< capnp::MessageBuilder > | **[builder_t](/libpalliate/generated/Namespaces/namespacetransport#using-builder-t)**  |

## Functions

|                | Name           |
| -------------- | -------------- |
| template <typename T \> <br>std::tuple< [transport::builder_t](/libpalliate/generated/Namespaces/namespacetransport#using-builder-t), typename T::Data::Builder > | **[build](/libpalliate/generated/Namespaces/namespacetransport#function-build)**() |

## Attributes

|                | Name           |
| -------------- | -------------- |
| uint64_t | **[uuid](/libpalliate/generated/Namespaces/namespacetransport#variable-uuid)**  |

## Types Documentation

### using reader_t

```cpp
using transport::reader_t = typedef std::unique_ptr<::capnp::MessageReader>;
```


### using builder_t

```cpp
using transport::builder_t = typedef std::unique_ptr<capnp::MessageBuilder>;
```



## Functions Documentation

### function build

```cpp
template <typename T >
inline std::tuple< transport::builder_t, typename T::Data::Builder > build()
```



## Attributes Documentation

### variable uuid

```cpp
uint64_t uuid;
```






_Automatically updated on 2022-05-02 at 01:42:11 +0000._