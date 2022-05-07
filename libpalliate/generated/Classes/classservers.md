---
title: servers
parent: Classes
grand_parent: libpalliate
layout: default
---

# servers






`#include <servers.h>`

## Public Functions

|                | Name           |
| -------------- | -------------- |
| void | **[add](/libpalliate/generated/Classes/classservers#function-add)**(std::unique_ptr< [server](/libpalliate/generated/Classes/classtransport_1_1server) > handle) |
| void | **[remove](/libpalliate/generated/Classes/classservers#function-remove)**([server](/libpalliate/generated/Classes/classtransport_1_1server) * handle) |
| void | **[broadcast](/libpalliate/generated/Classes/classservers#function-broadcast)**(capnp::MessageBuilder * message) |
| void | **[set_event](/libpalliate/generated/Classes/classservers#function-set-event)**(std::function< void([client](/libpalliate/generated/Classes/classtransport_1_1client) *, [reader_t](/libpalliate/generated/Namespaces/namespacetransport#using-reader-t))> message_event) |

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



_Automatically updated on 2022-05-07 at 23:35:51 +0000._