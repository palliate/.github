---
title: transport::server
parent: Classes
grand_parent: libpalliate
layout: default
---

# transport::server






`#include <server.h>`

Inherits from [runnable](/libpalliate/generated/Classes/classrunnable)

Inherited by [transport::tcp::server](/libpalliate/generated/Classes/classtransport_1_1tcp_1_1server)

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[~server](/libpalliate/generated/Classes/classtransport_1_1server#function-~server)**() override =default |
| | **[server](/libpalliate/generated/Classes/classtransport_1_1server#function-server)**(std::string const & _name, bool _packed =false) |
| virtual [builder_t](/libpalliate/generated/Namespaces/namespacetransport#using-builder-t) | **[prepare](/libpalliate/generated/Classes/classtransport_1_1server#function-prepare)**() |
| void | **[broadcast](/libpalliate/generated/Classes/classtransport_1_1server#function-broadcast)**(capnp::MessageBuilder * message) |
| void | **[set_event](/libpalliate/generated/Classes/classtransport_1_1server#function-set-event)**(std::function< void([client](/libpalliate/generated/Classes/classtransport_1_1client) *, [reader_t](/libpalliate/generated/Namespaces/namespacetransport#using-reader-t))> message_event) |
| void | **[add](/libpalliate/generated/Classes/classtransport_1_1server#function-add)**(std::unique_ptr< [client](/libpalliate/generated/Classes/classtransport_1_1client) > clientobj) |
| void | **[remove](/libpalliate/generated/Classes/classtransport_1_1server#function-remove)**([client](/libpalliate/generated/Classes/classtransport_1_1client) * obj) |

## Protected Attributes

|                | Name           |
| -------------- | -------------- |
| std::list< std::unique_ptr< [client](/libpalliate/generated/Classes/classtransport_1_1client) > > | **[clients](/libpalliate/generated/Classes/classtransport_1_1server#variable-clients)**  |
| std::mutex | **[clients_mutex](/libpalliate/generated/Classes/classtransport_1_1server#variable-clients-mutex)**  |
| bool | **[packed](/libpalliate/generated/Classes/classtransport_1_1server#variable-packed)**  |
| std::function< void([client](/libpalliate/generated/Classes/classtransport_1_1client) *, [reader_t](/libpalliate/generated/Namespaces/namespacetransport#using-reader-t))> | **[message_event](/libpalliate/generated/Classes/classtransport_1_1server#variable-message-event)**  |

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

**Protected Functions inherited from [runnable](/libpalliate/generated/Classes/classrunnable)**

|                | Name           |
| -------------- | -------------- |
| virtual bool | **[loop](/libpalliate/generated/Classes/classrunnable#function-loop)**() =0 |

**Protected Attributes inherited from [runnable](/libpalliate/generated/Classes/classrunnable)**

|                | Name           |
| -------------- | -------------- |
| std::jthread | **[thread](/libpalliate/generated/Classes/classrunnable#variable-thread)**  |
| std::unique_ptr< [callback_t](/libpalliate/generated/Classes/classrunnable#using-callback-t) > | **[callback](/libpalliate/generated/Classes/classrunnable#variable-callback)**  |
| const std::string | **[name](/libpalliate/generated/Classes/classrunnable#variable-name)**  |


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



_Automatically updated on 2022-05-02 at 01:49:10 +0000._