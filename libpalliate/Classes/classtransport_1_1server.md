---
title: transport::server

---

# transport::server






`#include <server.h>`

Inherits from [runnable](Classes/classrunnable.md)

Inherited by [transport::tcp::server](Classes/classtransport_1_1tcp_1_1server.md)

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[~server](Classes/classtransport_1_1server.md#function-~server)**() override =default |
| | **[server](Classes/classtransport_1_1server.md#function-server)**(std::string const & _name, bool _packed =false) |
| virtual [builder_t](Namespaces/namespacetransport.md#using-builder-t) | **[prepare](Classes/classtransport_1_1server.md#function-prepare)**() |
| void | **[broadcast](Classes/classtransport_1_1server.md#function-broadcast)**(capnp::MessageBuilder * message) |
| void | **[set_event](Classes/classtransport_1_1server.md#function-set-event)**(std::function< void([client](Classes/classtransport_1_1client.md) *, [reader_t](Namespaces/namespacetransport.md#using-reader-t))> message_event) |
| void | **[add](Classes/classtransport_1_1server.md#function-add)**(std::unique_ptr< [client](Classes/classtransport_1_1client.md) > clientobj) |
| void | **[remove](Classes/classtransport_1_1server.md#function-remove)**([client](Classes/classtransport_1_1client.md) * obj) |

## Protected Attributes

|                | Name           |
| -------------- | -------------- |
| std::list< std::unique_ptr< [client](Classes/classtransport_1_1client.md) > > | **[clients](Classes/classtransport_1_1server.md#variable-clients)**  |
| std::mutex | **[clients_mutex](Classes/classtransport_1_1server.md#variable-clients-mutex)**  |
| bool | **[packed](Classes/classtransport_1_1server.md#variable-packed)**  |
| std::function< void([client](Classes/classtransport_1_1client.md) *, [reader_t](Namespaces/namespacetransport.md#using-reader-t))> | **[message_event](Classes/classtransport_1_1server.md#variable-message-event)**  |

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

### function ~server

```cpp
~server() override =default
```


### function server

```cpp
inline server(
    std::string const & _name,
    bool _packed =false
)
```


### function prepare

```cpp
virtual builder_t prepare()
```


### function broadcast

```cpp
void broadcast(
    capnp::MessageBuilder * message
)
```


### function set_event

```cpp
void set_event(
    std::function< void(client *, reader_t)> message_event
)
```


### function add

```cpp
void add(
    std::unique_ptr< client > clientobj
)
```


### function remove

```cpp
void remove(
    client * obj
)
```


## Protected Attributes Documentation

### variable clients

```cpp
std::list< std::unique_ptr< client > > clients;
```


### variable clients_mutex

```cpp
std::mutex clients_mutex;
```


### variable packed

```cpp
bool packed;
```


### variable message_event

```cpp
std::function< void(client *, reader_t)> message_event;
```


-------------------------------

Updated on 2022-04-30 at 06:56:37 +0000