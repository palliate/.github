---
title: transport::tcp::client

---

# transport::tcp::client






`#include <client.h>`

Inherits from [transport::client](Classes/classtransport_1_1client.md), [runnable](Classes/classrunnable.md)

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[client](Classes/classtransport_1_1tcp_1_1client.md#function-client)**(int _fd, bool _packed =false) |
| | **[client](Classes/classtransport_1_1tcp_1_1client.md#function-client)**(const char * host, unsigned port, bool _packed =false) |
| | **[~client](Classes/classtransport_1_1tcp_1_1client.md#function-~client)**() override |
| virtual void | **[send](Classes/classtransport_1_1tcp_1_1client.md#function-send)**(capnp::MessageBuilder * message) override |
| virtual [reader_t](Namespaces/namespacetransport.md#using-reader-t) | **[recv](Classes/classtransport_1_1tcp_1_1client.md#function-recv)**() override |

## Additional inherited members

**Public Functions inherited from [transport::client](Classes/classtransport_1_1client.md)**

|                | Name           |
| -------------- | -------------- |
| virtual bool | **[loop](Classes/classtransport_1_1client.md#function-loop)**() |

**Public Attributes inherited from [transport::client](Classes/classtransport_1_1client.md)**

|                | Name           |
| -------------- | -------------- |
| std::function< void([client](Classes/classtransport_1_1client.md) *, [reader_t](Namespaces/namespacetransport.md#using-reader-t))> | **[message_event](Classes/classtransport_1_1client.md#variable-message-event)**  |

**Protected Attributes inherited from [transport::client](Classes/classtransport_1_1client.md)**

|                | Name           |
| -------------- | -------------- |
| bool | **[packed](Classes/classtransport_1_1client.md#variable-packed)**  |

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

**Protected Functions inherited from [runnable](Classes/classrunnable.md)**

|                | Name           |
| -------------- | -------------- |
| virtual bool | **[loop](Classes/classrunnable.md#function-loop)**() =0 |

**Protected Attributes inherited from [runnable](Classes/classrunnable.md)**

|                | Name           |
| -------------- | -------------- |
| std::jthread | **[thread](Classes/classrunnable.md#variable-thread)**  |
| std::unique_ptr< [callback_t](Classes/classrunnable.md#using-callback-t) > | **[callback](Classes/classrunnable.md#variable-callback)**  |
| const std::string | **[name](Classes/classrunnable.md#variable-name)**  |


## Public Functions Documentation

### function client

```cpp
explicit client(
    int _fd,
    bool _packed =false
)
```


### function client

```cpp
client(
    const char * host,
    unsigned port,
    bool _packed =false
)
```


### function ~client

```cpp
~client() override
```


### function send

```cpp
virtual void send(
    capnp::MessageBuilder * message
) override
```


**Reimplements**: [transport::client::send](Classes/classtransport_1_1client.md#function-send)


### function recv

```cpp
virtual reader_t recv() override
```


**Reimplements**: [transport::client::recv](Classes/classtransport_1_1client.md#function-recv)


-------------------------------

Updated on 2022-04-30 at 06:56:37 +0000