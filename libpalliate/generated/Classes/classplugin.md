---
title: plugin
parent: Classes
grand_parent: libpalliate
layout: default
---

# plugin






`#include <plugin.h>`

## Public Types

|                | Name           |
| -------------- | -------------- |
| using std::shared_ptr< [plugin](/libpalliate/generated/Classes/classplugin) >(*)() | **[init_f](/libpalliate/generated/Classes/classplugin#using-init-f)**  |

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[plugin](/libpalliate/generated/Classes/classplugin#function-plugin)**(std::string_view _name) |
| virtual | **[~plugin](/libpalliate/generated/Classes/classplugin#function-~plugin)**() =default |
| virtual std::unique_ptr< [consumer](/libpalliate/generated/Classes/classconsumer) > | **[make_consumer](/libpalliate/generated/Classes/classplugin#function-make-consumer)**([transport::client](/libpalliate/generated/Classes/classtransport_1_1client) & handle) =0 |
| virtual std::unique_ptr< [producer](/libpalliate/generated/Classes/classproducer) > | **[make_producer](/libpalliate/generated/Classes/classplugin#function-make-producer)**() =0 |

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| std::string_view | **[name](/libpalliate/generated/Classes/classplugin#variable-name)**  |

## Public Types Documentation

### using init_f

```cpp
using plugin::init_f =  std::shared_ptr<plugin> (*)();
```


## Public Functions Documentation

### function plugin

```cpp
inline explicit plugin(
    std::string_view _name
)
```


### function ~plugin

```cpp
virtual ~plugin() =default
```


### function make_consumer

```cpp
virtual std::unique_ptr< consumer > make_consumer(
    transport::client & handle
) =0
```


### function make_producer

```cpp
virtual std::unique_ptr< producer > make_producer() =0
```


## Public Attributes Documentation

### variable name

```cpp
std::string_view name;
```



_Automatically updated on 2022-05-07 at 23:35:51 +0000._