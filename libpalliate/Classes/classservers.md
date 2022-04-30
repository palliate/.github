---
title: servers

---

# servers






`#include <servers.h>`

## Public Functions

|                | Name           |
| -------------- | -------------- |
| void | **[add](Classes/classservers.md#function-add)**(std::unique_ptr< [server](Classes/classtransport_1_1server.md) > handle) |
| void | **[remove](Classes/classservers.md#function-remove)**([server](Classes/classtransport_1_1server.md) * handle) |
| void | **[broadcast](Classes/classservers.md#function-broadcast)**(capnp::MessageBuilder * message) |
| void | **[set_event](Classes/classservers.md#function-set-event)**(std::function< void([client](Classes/classtransport_1_1client.md) *, [reader_t](Namespaces/namespacetransport.md#using-reader-t))> message_event) |

## Public Functions Documentation

### function add

```cpp
void add(
    std::unique_ptr< server > handle
)
```


### function remove

```cpp
void remove(
    server * handle
)
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


-------------------------------

Updated on 2022-04-30 at 06:56:37 +0000