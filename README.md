# Object-Oriented Programming in Java — Lab Portfolio & Projects

**Student Details:**
- **Student Name:** Anesu B Kahanda
- **Registration Number:** H250407A
- **Department:** Computer Science
- **Level:** Undergraduate Computer Science (Year 2)

---

## Portfolio Directory Structure

This repository contains all 11 laboratory modules and the capstone mini-project specified in the University Lab Manual. Each module is housed in its own dedicated directory with complete source code, exercises, meaningful comments, and comprehensive README documentation.

```
Projects/
├── Lab01_Classes_and_Objects/
├── Lab02_Constructors_This_Static/
├── Lab03_Encapsulation/
├── Lab04_Inheritance/
├── Lab05_Polymorphism/
├── Lab06_Abstraction/
├── Lab07_Exception_Handling/
├── Lab08_Generics_and_Collections/
├── Lab09_Nested_Types_Enums_Records/
├── Lab10_File_IO_Lambdas_Streams/
├── Lab11_Design_Patterns/
├── MiniProject_Library_Management_System/
└── Assignment/
```

---

## Laboratory Modules Summary

| Module Folder | Topic | Core OOP Concepts Covered |
|---|---|---|
| [`Assignment`](https://github.com/h250407a/Assignment) | Practical Assignment: Bank System | Abstract base class, inheritance, polymorphism, dynamic method dispatch, overdraft & interest rules. |
| [`Lab01_Classes_and_Objects`](https://github.com/h250407a/Lab01_Classes_and_Objects) | Classes and Objects | Fields, methods, heap references, aliasing, and null safety. |
| [`Lab02_Constructors_This_Static`](https://github.com/h250407a/Lab02_Constructors_This_Static) | Constructors & Static Members | Constructor overloading, chaining with `this(...)`, static fields/counters, copy constructors, and initializer blocks. |
| [`Lab03_Encapsulation`](https://github.com/h250407a/Lab03_Encapsulation) | Encapsulation & Data Hiding | Private fields, validation invariants, defensive copies, and immutable classes. |
| [`Lab04_Inheritance`](https://github.com/h250407a/Lab04_Inheritance) | Inheritance & Composition | Subclassing with `extends`, `super(...)`, protected access, overriding, and composition over inheritance. |
| [`Lab05_Polymorphism`](https://github.com/h250407a/Lab05_Polymorphism) | Polymorphism | Method overloading (compile-time), method overriding (runtime dynamic dispatch), and pattern matching `instanceof`. |
| [`Lab06_Abstraction`](https://github.com/h250407a/Lab06_Abstraction) | Abstraction & Interfaces | Abstract classes, interfaces, default/static interface methods, and `Comparable` natural ordering. |
| [`Lab07_Exception_Handling`](https://github.com/h250407a/Lab07_Exception_Handling) | Exception Handling | Try-catch-finally, custom checked exceptions, `try-with-resources`, and exception chaining. |
| [`Lab08_Generics_and_Collections`](https://github.com/h250407a/Lab08_Generics_and_Collections) | Generics & Collections | Generic classes/methods, bounded type parameters, `List`, `Set`, `Map`, `Deque`, and custom stack. |
| [`Lab09_Nested_Types_Enums_Records`](https://github.com/h250407a/Lab09_Nested_Types_Enums_Records) | Enums, Records & Objects | Static nested/inner classes, type-safe enums, Java records, and `equals`/`hashCode` contracts. |
| [`Lab10_File_IO_Lambdas_Streams`](https://github.com/h250407a/Lab10_File_IO_Lambdas_Streams) | File I/O, Lambdas & Streams | `java.nio.file`, CSV persistence, functional interfaces, and declarative stream pipelines. |
| [`Lab11_Design_Patterns`](https://github.com/h250407a/Lab11_Design_Patterns) | Design Patterns | Singleton, Factory, Strategy, and Observer design patterns. |
| [`MiniProject_Library_Management_System`](https://github.com/h250407a/MiniProject_Library_Management_System) | Capstone Mini-Project | Full console Library Management System integrating abstraction, inheritance, interfaces, custom exceptions, streams, and CSV persistence. |

---

## Quick Compilation & Execution Guide

To compile any individual laboratory module, navigate into its folder and execute:
```bash
cd <Folder_Name>
javac *.java
```

For instance, to run the capstone Mini-Project:
```bash
cd MiniProject_Library_Management_System
javac *.java
java LibraryApp
```
