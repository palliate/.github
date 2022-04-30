---
title: transport::client

---

# transport::client






`#include <client.h>`

Inherits from [runnable](Classes/classrunnable.md)

Inherited by [transport::tcp::client](Classes/classtransport_1_1tcp_1_1client.md)

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[client](Classes/classtransport_1_1client.md#function-client)**(std::string const & _name, bool _packed =false) |
| | **[~client](Classes/classtransport_1_1client.md#function-~client)**() override |
| virtual bool | **[loop](Classes/classtransport_1_1client.md#function-loop)**() |
| virtual void | **[send](Classes/classtransport_1_1client.md#function-send)**(capnp::MessageBuilder * message) =0 |
| virtual [reader_t](Namespaces/namespacetransport.md#using-reader-t) | **[recv](Classes/classtransport_1_1client.md#function-recv)**() =0 |

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| std::function< void([client](Classes/classtransport_1_1client.md) *, [reader_t](Namespaces/namespacetransport.md#using-reader-t))> | **[message_event](Classes/classtransport_1_1client.md#variable-message-event)**  |

## Protected Attributes

|                | Name           |
| -------------- | -------------- |
| bool | **[packed](Classes/classtransport_1_1client.md#variable-packed)**  |

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

### function client

```cpp
inline explicit client(
    std::string const & _name,
    bool _packed =false
)
```


### function ~client

```cpp
~client() override
```


### function loop

```cpp
virtual bool loop()
```


**Reimplements**: [runnable::loop](Classes/classrunnable.md#function-loop)


### function send

```cpp
virtual void send(
    capnp::MessageBuilder * message
) =0
```


**Reimplemented by**: [transport::tcp::client::send](Classes/classtransport_1_1tcp_1_1client.md#function-send)


### function recv

```cpp
virtual reader_t recv() =0
```


**Reimplemented by**: [transport::tcp::client::recv](Classes/classtransport_1_1tcp_1_1client.md#function-recv)


## Public Attributes Documentation

### variable message_event

```cpp
std::function< void(client *, reader_t)> message_event;
```


## Protected Attributes Documentation

### variable packed

```cpp
bool packed;
```


-------------------------------

Updated on 2022-04-30 at 06:56:37 +0000