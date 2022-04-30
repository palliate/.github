---
title: transport::tcp::server

---

# transport::tcp::server






`#include <server.h>`

Inherits from [transport::server](Classes/classtransport_1_1server.md), [runnable](Classes/classrunnable.md)

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[server](Classes/classtransport_1_1tcp_1_1server.md#function-server)**(const char * _host, unsigned _port, bool _packed =false) |
| virtual bool | **[loop](Classes/classtransport_1_1tcp_1_1server.md#function-loop)**() override |

## Additional inherited members

**Public Functions inherited from [transport::server](Classes/classtransport_1_1server.md)**

|                | Name           |
| -------------- | -------------- |
| | **[~server](Classes/classtransport_1_1server.md#function-~server)**() override =default |
| virtual [builder_t](Namespaces/namespacetransport.md#using-builder-t) | **[prepare](Classes/classtransport_1_1server.md#function-prepare)**() |
| void | **[broadcast](Classes/classtransport_1_1server.md#function-broadcast)**(capnp::MessageBuilder * message) |
| void | **[set_event](Classes/classtransport_1_1server.md#function-set-event)**(std::function< void([client](Classes/classtransport_1_1client.md) *, [reader_t](Namespaces/namespacetransport.md#using-reader-t))> message_event) |
| void | **[add](Classes/classtransport_1_1server.md#function-add)**(std::unique_ptr< [client](Classes/classtransport_1_1client.md) > clientobj) |
| void | **[remove](Classes/classtransport_1_1server.md#function-remove)**([client](Classes/classtransport_1_1client.md) * obj) |

**Protected Attributes inherited from [transport::server](Classes/classtransport_1_1server.md)**

|                | Name           |
| -------------- | -------------- |
| std::list< std::unique_ptr< [client](Classes/classtransport_1_1client.md) > > | **[clients](Classes/classtransport_1_1server.md#variable-clients)**  |
| std::mutex | **[clients_mutex](Classes/classtransport_1_1server.md#variable-clients-mutex)**  |
| bool | **[packed](Classes/classtransport_1_1server.md#variable-packed)**  |
| std::function< void([client](Classes/classtransport_1_1client.md) *, [reader_t](Namespaces/namespacetransport.md#using-reader-t))> | **[message_event](Classes/classtransport_1_1server.md#variable-message-event)**  |

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

### function server

```cpp
server(
    const char * _host,
    unsigned _port,
    bool _packed =false
)
```


### function loop

```cpp
virtual bool loop() override
```


**Reimplements**: [runnable::loop](Classes/classrunnable.md#function-loop)


-------------------------------

Updated on 2022-04-30 at 06:56:37 +0000