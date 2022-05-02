---
title: runnable
parent: Classes
grand_parent: libpalliate
layout: default
---

# runnable






`#include <runnable.h>`

Inherited by [consumer](/libpalliate/generated/Classes/classconsumer), [producer](/libpalliate/generated/Classes/classproducer), [transport::client](/libpalliate/generated/Classes/classtransport_1_1client), [transport::server](/libpalliate/generated/Classes/classtransport_1_1server), [ui](/libpalliate/generated/Classes/classui)

## Public Types

|                | Name           |
| -------------- | -------------- |
| using std::function< void()> | **[callback_f](/libpalliate/generated/Classes/classrunnable#using-callback-f)**  |
| using std::stop_callback< [callback_f](/libpalliate/generated/Classes/classrunnable#using-callback-f) > | **[callback_t](/libpalliate/generated/Classes/classrunnable#using-callback-t)**  |

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[runnable](/libpalliate/generated/Classes/classrunnable#function-runnable)**(std::string const & _name) |
| virtual | **[~runnable](/libpalliate/generated/Classes/classrunnable#function-~runnable)**() |
| virtual void | **[operator()](/libpalliate/generated/Classes/classrunnable#function-operator())**(std::stop_token token ={}) |
| void | **[run](/libpalliate/generated/Classes/classrunnable#function-run)**() |
| void | **[run](/libpalliate/generated/Classes/classrunnable#function-run)**([callback_f](/libpalliate/generated/Classes/classrunnable#using-callback-f) _callback) |
| void | **[stop](/libpalliate/generated/Classes/classrunnable#function-stop)**() |
| auto | **[operator](/libpalliate/generated/Classes/classrunnable#function-operator)**([runnable](/libpalliate/generated/Classes/classrunnable) const & other) const |

## Protected Functions

|                | Name           |
| -------------- | -------------- |
| virtual bool | **[loop](/libpalliate/generated/Classes/classrunnable#function-loop)**() =0 |

## Protected Attributes

|                | Name           |
| -------------- | -------------- |
| std::jthread | **[thread](/libpalliate/generated/Classes/classrunnable#variable-thread)**  |
| std::unique_ptr< [callback_t](/libpalliate/generated/Classes/classrunnable#using-callback-t) > | **[callback](/libpalliate/generated/Classes/classrunnable#variable-callback)**  |
| const std::string | **[name](/libpalliate/generated/Classes/classrunnable#variable-name)**  |

## Public Types Documentation

### using callback_f

```cpp
using runnable::callback_f =  std::function<void()>;
```


### using callback_t

```cpp
using runnable::callback_t =  std::stop_callback<callback_f>;
```


## Public Functions Documentation

### function runnable

```cpp
inline explicit runnable(
    std::string const & _name
)
```


### function ~runnable

```cpp
virtual ~runnable()
```


### function operator()

```cpp
virtual void operator()(
    std::stop_token token ={}
)
```


### function run

```cpp
void run()
```


### function run

```cpp
void run(
    callback_f _callback
)
```


### function stop

```cpp
void stop()
```


### function operator

```cpp
auto operator(
    runnable const & other
) const
```


## Protected Functions Documentation

### function loop

```cpp
virtual bool loop() =0
```


**Reimplemented by**: [transport::client::loop](/libpalliate/generated/Classes/classtransport_1_1client#function-loop), [consumer::loop](/libpalliate/generated/Classes/classconsumer#function-loop), [transport::tcp::server::loop](/libpalliate/generated/Classes/classtransport_1_1tcp_1_1server#function-loop), [producer::loop](/libpalliate/generated/Classes/classproducer#function-loop), [ui::loop](/libpalliate/generated/Classes/classui#function-loop)


## Protected Attributes Documentation

### variable thread

```cpp
std::jthread thread;
```


### variable callback

```cpp
std::unique_ptr< callback_t > callback;
```


### variable name

```cpp
const std::string name;
```



_Automatically updated on 2022-05-02 at 01:42:07 +0000._