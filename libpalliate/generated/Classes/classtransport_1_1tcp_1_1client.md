---
title: transport::tcp::client
parent: Classes
grand_parent: libpalliate
layout: default
---

# transport::tcp::client






`#include <client.h>`

Inherits from [transport::client](/libpalliate/generated/Classes/classtransport_1_1client), [runnable](/libpalliate/generated/Classes/classrunnable)

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[client](/libpalliate/generated/Classes/classtransport_1_1tcp_1_1client#function-client)**(int _fd, bool _packed =false) |
| | **[client](/libpalliate/generated/Classes/classtransport_1_1tcp_1_1client#function-client)**(const char * host, unsigned port, bool _packed =false) |
| | **[~client](/libpalliate/generated/Classes/classtransport_1_1tcp_1_1client#function-~client)**() override |
| virtual void | **[send](/libpalliate/generated/Classes/classtransport_1_1tcp_1_1client#function-send)**(capnp::MessageBuilder * message) override |
| virtual [reader_t](/libpalliate/generated/Namespaces/namespacetransport#using-reader-t) | **[recv](/libpalliate/generated/Classes/classtransport_1_1tcp_1_1client#function-recv)**() override |

## Additional inherited members

**Public Functions inherited from [transport::client](/libpalliate/generated/Classes/classtransport_1_1client)**

|                | Name           |
| -------------- | -------------- |
| virtual bool | **[loop](/libpalliate/generated/Classes/classtransport_1_1client#function-loop)**() |

**Public Attributes inherited from [transport::client](/libpalliate/generated/Classes/classtransport_1_1client)**

|                | Name           |
| -------------- | -------------- |
| std::function< void([client](/libpalliate/generated/Classes/classtransport_1_1client) *, [reader_t](/libpalliate/generated/Namespaces/namespacetransport#using-reader-t))> | **[message_event](/libpalliate/generated/Classes/classtransport_1_1client#variable-message-event)**  |

**Protected Attributes inherited from [transport::client](/libpalliate/generated/Classes/classtransport_1_1client)**

|                | Name           |
| -------------- | -------------- |
| bool | **[packed](/libpalliate/generated/Classes/classtransport_1_1client#variable-packed)**  |

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


**Reimplements**: [transport::client::send](/libpalliate/generated/Classes/classtransport_1_1client#function-send)


### function recv

```cpp
virtual reader_t recv() override
```


**Reimplements**: [transport::client::recv](/libpalliate/generated/Classes/classtransport_1_1client#function-recv)



_Automatically updated on 2022-05-02 at 01:42:11 +0000._