---
title: consumer

---

# consumer






`#include <consumer.h>`

Inherits from [runnable](Classes/classrunnable.md)

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[~consumer](Classes/classconsumer.md#function-~consumer)**() override =default |
| | **[consumer](Classes/classconsumer.md#function-consumer)**(std::string const & _name, [transport::client](Classes/classtransport_1_1client.md) & _handle) |
| virtual bool | **[loop](Classes/classconsumer.md#function-loop)**() override |
| virtual void | **[handle](Classes/classconsumer.md#function-handle)**([transport::reader_t](Namespaces/namespacetransport.md#using-reader-t) message) =0 |

## Protected Attributes

|                | Name           |
| -------------- | -------------- |
| [transport::client](Classes/classtransport_1_1client.md) & | **[client_handle](Classes/classconsumer.md#variable-client-handle)**  |

## Additional inherited members

**Public Types inherited from [runnable](Classes/classrunnable.md)**

|                | Name           |
| -------------- | -------------- |
| using std::function< void()> | **[callback_f](Classes/classrunnable.md#using-callback-f)**  |
| using std::stop_callback< [callback_f](Classes/classrunnable.md#using-callback-f) > | **[callback_t](Classes/classrunnable.md#using-callback-t)**  |

**Public Functions inherited from [runnable](Classes/classrunnable.md)**

|                | Name           |
| -------------- | -------------- |
| | **[runnable](Classes/classrunnable.md#function-runnable)**(std::string const & _name) |
| virtual | **[~runnable](Classes/classrunnable.md#function-~runnable)**() |
| virtual void | **[operator()](Classes/classrunnable.md#function-operator())**(std::stop_token token ={}) |
| void | **[run](Classes/classrunnable.md#function-run)**() |
| void | **[run](Classes/classrunnable.md#function-run)**([callback_f](Classes/classrunnable.md#using-callback-f) _callback) |
| void | **[stop](Classes/classrunnable.md#function-stop)**() |
| auto | **[operator](Classes/classrunnable.md#function-operator)**([runnable](Classes/classrunnable.md) const & other) const |

**Protected Attributes inherited from [runnable](Classes/classrunnable.md)**

|                | Name           |
| -------------- | -------------- |
| std::jthread | **[thread](Classes/classrunnable.md#variable-thread)**  |
| std::unique_ptr< [callback_t](Classes/classrunnable.md#using-callback-t) > | **[callback](Classes/classrunnable.md#variable-callback)**  |
| const std::string | **[name](Classes/classrunnable.md#variable-name)**  |


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


**Reimplements**: [runnable::loop](Classes/classrunnable.md#function-loop)


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


-------------------------------

Updated on 2022-04-30 at 06:56:37 +0000