# Custom Dynamic Array — C++

## Overview

A custom templated dynamic array implemented in C++ to explore how dynamically allocated containers manage memory, ownership, and object lifetimes.

Developed as a hands-on learning project, the implementation focuses on building fundamental container functionality from scratch, with particular attention to copy and move semantics.

## Features

- **Templated container:** Supports different element types through `IlariaVector<T>`.
- **Dynamic memory allocation:** Manages an underlying array using `new[]` and `delete[]`.
- **Automatic capacity growth:** Doubles allocated capacity when additional storage is needed.
- **Deep copying:** Implements a copy constructor and copy assignment operator to create independent copies of the underlying storage.
- **Move semantics:** Implements a move constructor and move assignment operator to transfer ownership of dynamically allocated memory.
- **Element operations:** Supports insertion at the end, indexed access, replacement, and removal.
- **Resource cleanup:** Uses a destructor to release allocated storage.

## Technical Concepts

- C++ templates
- Manual memory management
- RAII and resource ownership
- Rule of Five
- Copy and move semantics
- Dynamic arrays and capacity management
- Operator overloading

## Learning Objectives

The project was developed to deepen my understanding of how C++ containers work internally, particularly the relationship between dynamically allocated memory, object lifetimes, and copy/move operations.

Implementing these mechanisms manually also provided practical experience with the responsibilities involved in managing resources without relying on standard library containers.

## Limitations

This is an educational implementation, not a complete replacement for `std::vector`. It focuses on fundamental memory-management and container operations rather than full standard-library compatibility.
