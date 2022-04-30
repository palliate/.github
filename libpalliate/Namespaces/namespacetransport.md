---
title: transport

---

# transport



## Namespaces

| Name           |
| -------------- |
| **[transport::tcp](Namespaces/namespacetransport_1_1tcp.md)**  |

## Classes

|                | Name           |
| -------------- | -------------- |
| class | **[transport::client](Classes/classtransport_1_1client.md)**  |
| class | **[transport::server](Classes/classtransport_1_1server.md)**  |

## Types

|                | Name           |
| -------------- | -------------- |
| using std::unique_ptr<::capnp::MessageReader > | **[reader_t](Namespaces/namespacetransport.md#using-reader-t)**  |
| using std::unique_ptr< capnp::MessageBuilder > | **[builder_t](Namespaces/namespacetransport.md#using-builder-t)**  |

## Functions

|                | Name           |
| -------------- | -------------- |
| template <typename T \> <br>std::tuple< [transport::builder_t](Namespaces/namespacetransport.md#using-builder-t), typename T::Data::Builder > | **[build](Namespaces/namespacetransport.md#function-build)**() |

## Attributes

|                | Name           |
| -------------- | -------------- |
| uint64_t | **[uuid](Namespaces/namespacetransport.md#variable-uuid)**  |

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





-------------------------------

Updated on 2022-04-30 at 06:56:37 +0000