---
title: runnable

---

# runnable






`#include <runnable.h>`

Inherited by [consumer](Classes/classconsumer.md), [producer](Classes/classproducer.md), [transport::client](Classes/classtransport_1_1client.md), [transport::server](Classes/classtransport_1_1server.md), [ui](Classes/classui.md)

## Public Types

|                | Name           |
| -------------- | -------------- |
| using std::function< void()> | **[callback_f](Classes/classrunnable.md#using-callback-f)**  |
| using std::stop_callback< [callback_f](Classes/classrunnable.md#using-callback-f) > | **[callback_t](Classes/classrunnable.md#using-callback-t)**  |

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[runnable](Classes/classrunnable.md#function-runnable)**(std::string const & _name) |
| virtual | **[~runnable](Classes/classrunnable.md#function-~runnable)**() |
| virtual void | **[operator()](Classes/classrunnable.md#function-operator())**(std::stop_token token ={}) |
| void | **[run](Classes/classrunnable.md#function-run)**() |
| void | **[run](Classes/classrunnable.md#function-run)**([callback_f](Classes/classrunnable.md#using-callback-f) _callback) |
| void | **[stop](Classes/classrunnable.md#function-stop)**() |
| auto | **[operator](Classes/classrunnable.md#function-operator)**([runnable](Classes/classrunnable.md) const & other) const |

## Protected Functions

|                | Name           |
| -------------- | -------------- |
| virtual bool | **[loop](Classes/classrunnable.md#function-loop)**() =0 |

## Protected Attributes

|                | Name           |
| -------------- | -------------- |
| std::jthread | **[thread](Classes/classrunnable.md#variable-thread)**  |
| std::unique_ptr< [callback_t](Classes/classrunnable.md#using-callback-t) > | **[callback](Classes/classrunnable.md#variable-callback)**  |
| const std::string | **[name](Classes/classrunnable.md#variable-name)**  |

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


**Reimplemented by**: [transport::client::loop](Classes/classtransport_1_1client.md#function-loop), [consumer::loop](Classes/classconsumer.md#function-loop), [transport::tcp::server::loop](Classes/classtransport_1_1tcp_1_1server.md#function-loop), [producer::loop](Classes/classproducer.md#function-loop), [ui::loop](Classes/classui.md#function-loop)


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


-------------------------------

Updated on 2022-04-30 at 06:56:37 +0000