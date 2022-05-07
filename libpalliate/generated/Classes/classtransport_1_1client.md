---
title: transport::client
parent: Classes
grand_parent: libpalliate
layout: default
---

# transport::client






`#include <client.h>`

Inherits from [runnable](/libpalliate/generated/Classes/classrunnable)

Inherited by [transport::tcp::client](/libpalliate/generated/Classes/classtransport_1_1tcp_1_1client)

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[client](/libpalliate/generated/Classes/classtransport_1_1client#function-client)**(std::string const & _name, bool _packed =false) |
| | **[~client](/libpalliate/generated/Classes/classtransport_1_1client#function-~client)**() override |
| virtual bool | **[loop](/libpalliate/generated/Classes/classtransport_1_1client#function-loop)**() |
| virtual void | **[send](/libpalliate/generated/Classes/classtransport_1_1client#function-send)**(capnp::MessageBuilder * message) =0 |
| virtual [reader_t](/libpalliate/generated/Namespaces/namespacetransport#using-reader-t) | **[recv](/libpalliate/generated/Classes/classtransport_1_1client#function-recv)**() =0 |

## Public Attributes

|                | Name           |
| -------------- | -------------- |
| std::function< void([client](/libpalliate/generated/Classes/classtransport_1_1client) *, [reader_t](/libpalliate/generated/Namespaces/namespacetransport#using-reader-t))> | **[message_event](/libpalliate/generated/Classes/classtransport_1_1client#variable-message-event)**  |

## Protected Attributes

|                | Name           |
| -------------- | -------------- |
| bool | **[packed](/libpalliate/generated/Classes/classtransport_1_1client#variable-packed)**  |

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


**Reimplements**: [runnable::loop](/libpalliate/generated/Classes/classrunnable#function-loop)


### function send

```cpp
virtual void send(
    capnp::MessageBuilder * message
) =0
```


**Reimplemented by**: [transport::tcp::client::send](/libpalliate/generated/Classes/classtransport_1_1tcp_1_1client#function-send)


### function recv

```cpp
virtual reader_t recv() =0
```


**Reimplemented by**: [transport::tcp::client::recv](/libpalliate/generated/Classes/classtransport_1_1tcp_1_1client#function-recv)


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



_Automatically updated on 2022-05-07 at 23:06:39 +0000._