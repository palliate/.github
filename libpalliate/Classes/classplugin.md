---
title: plugin

---

# plugin






`#include <plugin.h>`

## Public Types

|                | Name           |
| -------------- | -------------- |
| using std::shared_ptr< [plugin](Classes/classplugin.md) >(*)() | **[init_f](Classes/classplugin.md#using-init-f)**  |

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[plugin](Classes/classplugin.md#function-plugin)**(std::string_view _name) |
| virtual | **[~plugin](Classes/classplugin.md#function-~plugin)**() =default |
| virtual std::unique_ptr< [consumer](Classes/classconsumer.md) > | **[make_consumer](Classes/classplugin.md#function-make-consumer)**([transport::client](Classes/classtransport_1_1client.md) & handle) =0 |
| virtual std::unique_ptr< [producer](Classes/classproducer.md) > | **[make_producer](Classes/classplugin.md#function-make-producer)**() =0 |

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| std::string_view | **[name](Classes/classplugin.md#variable-name)**  |

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


-------------------------------

Updated on 2022-04-30 at 06:56:37 +0000