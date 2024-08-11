# OOP Design Patterns in Machine Learning
Welcome to the "OOP Design Patterns in Machine Learning" project! This repository is designed to help you learn and apply Object-Oriented Programming (OOP) design patterns in the context of Machine Learning (ML). The project is structured to cover three major categories of design patterns: Creational, Behavioral, and Structural. The implementation is provided in both Python and Rust, allowing you to explore these concepts in two powerful languages.

## Project Structure
The repository is organized into three main directories, each corresponding to a category of design patterns:

```bash
- creational/
  - python/
  - rust/
- behavioral/
  - python/
  - rust/
- structural/
  - python/
  - rust/
```
Each directory contains implementations of the relevant design patterns in both Python and Rust. Inside each sub-directory, you'll find examples applied to common Machine Learning tasks, helping you understand how these patterns can be used to create scalable and maintainable ML code.

## Design Patterns Covered
### Creational Patterns
**Creational Patterns**
- Factory Method: Creates objects without specifying the exact class of object that will be created.
- Abstract Factory: Provides an interface for creating families of related or dependent objects without specifying their concrete classes.
- Singleton: Ensures a class has only one instance and provides a global point of access to it.
- Builder: Constructs complex objects step by step, allowing for more control over the construction process.
- Prototype: Creates new objects by copying an existing object, known as the prototype.
  
**Structural Patterns**
- Decorator: Dynamically adds new behavior to an object without altering its structure.
- Proxy: Provides a surrogate or placeholder for another object to control access to it.
- Adapter: Allows incompatible interfaces to work together by converting one interface into another.
- Composite: Composes objects into tree structures to represent part-whole hierarchies, allowing individual objects and compositions to be treated uniformly.
- Bridge: Decouples an abstraction from its implementation, allowing the two to vary independently.
  
**Behavioral Patterns**
- Observer: Establishes a subscription mechanism to allow multiple objects to listen to and react to events.
- Visitor: Allows adding further operations to objects without having to modify them.
- Iterator: Provides a way to access the elements of an aggregate object sequentially without exposing its underlying representation.
- Strategy: Defines a family of algorithms, encapsulates each one, and makes them interchangeable.
- Chain of Responsibility: Passes a request along a chain of handlers until one of them handles the request.
### Examples
Each pattern comes with a detailed example that shows its application in a Machine Learning context. For instance, the Strategy pattern is used to switch between different optimization algorithms in a training process, while the Decorator pattern is applied to enhance models with additional functionality such as logging or monitoring.
