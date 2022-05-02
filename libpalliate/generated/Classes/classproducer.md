---
title: producer
parent: Classes
grand_parent: libpalliate
layout: default
---

# producer






`#include <producer.h>`

Inherits from [runnable](/libpalliate/generated/Classes/classrunnable)

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[producer](/libpalliate/generated/Classes/classproducer#function-producer)**(std::string const & _name) |
| | **[~producer](/libpalliate/generated/Classes/classproducer#function-~producer)**() override |

## Protected Functions

|                | Name           |
| -------------- | -------------- |
| virtual void | **[control_event](/libpalliate/generated/Classes/classproducer#function-control-event)**([client](/libpalliate/generated/Classes/classtransport_1_1client) * source, [reader_t](/libpalliate/generated/Namespaces/namespacetransport#using-reader-t) message) =0 |

## Protected Attributes

|                | Name           |
| -------------- | -------------- |
| [servers](/libpalliate/generated/Classes/classservers) | **[data](/libpalliate/generated/Classes/classproducer#variable-data)**  |
| [servers](/libpalliate/generated/Classes/classservers) | **[control](/libpalliate/generated/Classes/classproducer#variable-control)**  |

## Additional inherited members

**Public Types inherited from [runnable](/libpalliate/generated/Classes/classrunnable)**

|                | Name           |
| -------------- | -------------- |
| using std::function< void()> | **[callback_f](/libpalliate/generated/Classes/classrunnable#using-callback-f)**  |
| using std::stop_callback< [callback_f](/libpalliate/generated/Classes/classrunnable#using-callback-f) > | **[callback_t](/libpalliate/generated/Classes/classrunnable#using-callback-t)**  |

**Public Functions inherited from [runnable](/libpalliate/generated/Classes/classrunnable)**

|                | Name           |
| -------------- | -------------- |
| | **[runnable](/libpalliate/generated/Classes/classrunnable#function-runnable)**(std::string const & _name) |
| virtual | **[~runnable](/libpalliate/generated/Classes/classrunnable#function-~runnable)**() |
| virtual void | **[operator()](/libpalliate/generated/Classes/classrunnable#function-operator())**(std::stop_token token ={}) |
| void | **[run](/libpalliate/generated/Classes/classrunnable#function-run)**() |
| void | **[run](/libpalliate/generated/Classes/classrunnable#function-run)**([callback_f](/libpalliate/generated/Classes/classrunnable#using-callback-f) _callback) |
| void | **[stop](/libpalliate/generated/Classes/classrunnable#function-stop)**() |
| auto | **[operator](/libpalliate/generated/Classes/classrunnable#function-operator)**([runnable](/libpalliate/generated/Classes/classrunnable) const & other) const |

**Protected Attributes inherited from [runnable](/libpalliate/generated/Classes/classrunnable)**

|                | Name           |
| -------------- | -------------- |
| std::jthread | **[thread](/libpalliate/generated/Classes/classrunnable#variable-thread)**  |
| std::unique_ptr< [callback_t](/libpalliate/generated/Classes/classrunnable#using-callback-t) > | **[callback](/libpalliate/generated/Classes/classrunnable#variable-callback)**  |
| const std::string | **[name](/libpalliate/generated/Classes/classrunnable#variable-name)**  |


## Public Functions Documentation

### function producer

```cpp
explicit producer(
    std::string const & _name
)
```


### function ~producer

```cpp
inline ~producer() override
```


## Protected Functions Documentation

### function control_event

```cpp
virtual void control_event(
    client * source,
    reader_t message
) =0
```


## Protected Attributes Documentation

### variable data

```cpp
servers data;
```


### variable control

```cpp
servers control;
```



_Automatically updated on 2022-05-02 at 01:49:10 +0000._