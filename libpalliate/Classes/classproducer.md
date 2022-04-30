---
title: producer

---

# producer






`#include <producer.h>`

Inherits from [runnable](Classes/classrunnable.md)

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[producer](Classes/classproducer.md#function-producer)**(std::string const & _name) |
| | **[~producer](Classes/classproducer.md#function-~producer)**() override |

## Protected Functions

|                | Name           |
| -------------- | -------------- |
| virtual void | **[control_event](Classes/classproducer.md#function-control-event)**([client](Classes/classtransport_1_1client.md) * source, [reader_t](Namespaces/namespacetransport.md#using-reader-t) message) =0 |

## Protected Attributes

|                | Name           |
| -------------- | -------------- |
| [servers](Classes/classservers.md) | **[data](Classes/classproducer.md#variable-data)**  |
| [servers](Classes/classservers.md) | **[control](Classes/classproducer.md#variable-control)**  |

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

**Protected Attributes inherited from [runnable](Classes/classrunnable.md)**

|                | Name           |
| -------------- | -------------- |
| std::jthread | **[thread](Classes/classrunnable.md#variable-thread)**  |
| std::unique_ptr< [callback_t](Classes/classrunnable.md#using-callback-t) > | **[callback](Classes/classrunnable.md#variable-callback)**  |
| const std::string | **[name](Classes/classrunnable.md#variable-name)**  |


## Public Functions Documentation

### function producer

```cpp
explicit producer(
    std::string const & _name
)
```


### function ~producer

```cpp
inline ~producer() override
```


## Protected Functions Documentation

### function control_event

```cpp
virtual void control_event(
    client * source,
    reader_t message
) =0
```


## Protected Attributes Documentation

### variable data

```cpp
servers data;
```


### variable control

```cpp
servers control;
```


-------------------------------

Updated on 2022-04-30 at 06:56:37 +0000