---
title: consumer
parent: Classes
grand_parent: libpalliate
layout: default
---

# consumer






`#include <consumer.h>`

Inherits from [runnable](/libpalliate/generated/Classes/classrunnable)

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[~consumer](/libpalliate/generated/Classes/classconsumer#function-~consumer)**() override =default |
| | **[consumer](/libpalliate/generated/Classes/classconsumer#function-consumer)**(std::string const & _name, [transport::client](/libpalliate/generated/Classes/classtransport_1_1client) & _handle) |
| virtual bool | **[loop](/libpalliate/generated/Classes/classconsumer#function-loop)**() override |
| virtual void | **[handle](/libpalliate/generated/Classes/classconsumer#function-handle)**([transport::reader_t](/libpalliate/generated/Namespaces/namespacetransport#using-reader-t) message) =0 |

## Protected Attributes

|                | Name           |
| -------------- | -------------- |
| [transport::client](/libpalliate/generated/Classes/classtransport_1_1client) & | **[client_handle](/libpalliate/generated/Classes/classconsumer#variable-client-handle)**  |

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

### function ~consumer

```cpp
~consumer() override =default
```


### function consumer

```cpp
inline consumer(
    std::string const & _name,
    transport::client & _handle
)
```


### function loop

```cpp
virtual bool loop() override
```


**Reimplements**: [runnable::loop](/libpalliate/generated/Classes/classrunnable#function-loop)


### function handle

```cpp
virtual void handle(
    transport::reader_t message
) =0
```


## Protected Attributes Documentation

### variable client_handle

```cpp
transport::client & client_handle;
```



_Automatically updated on 2022-05-07 at 23:06:39 +0000._