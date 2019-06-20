# P4L4 Introduction

## Design Patterns
Common design solutions to a problem in context. 

## Example: Composite Pattern
The purpose of this design pattern is summed up nicely in [Wikipedia:](https://en.wikipedia.org/wiki/Composite_pattern) 

> In software engineering, the composite pattern is a partitioning design pattern. The composite pattern describes a group of objects that is treated the same way as a single instance of the same type of object. The intent of a composite is to "compose" objects into tree structures to represent part-whole hierarchies. Implementing the composite pattern lets clients treat individual objects and compositions uniformly.

## Categories of Patterns in Gang of Four
* Structural patterns
* Creational patterns
* Behaviors patterns

### Creational Patterns
Five creational patterns: 
- Singleton
- Prototype
- Builder
- Factory Method
- Abstract Factory

### Structural Patterns
- Composite
- Adapter
- Bridge
- Decorator
- Facade
- Flyweight
- Proxy

### Behavioral Patterns
Most complex. Describes interesting ways objects can interact:
- Chain of Responsibility
- Command
- Interpreter
- Iterator/Enumeration
- Mediator
- Memento
- Observer/Listener
- State
- Strategy
- Template Method
- Visitor

#### Depth in Singleton
**Intent:** insures a program has only one instance of the class (this is applicable to OsMowSis).

**Participants:** just the singleton class

**Collaboration:** clients accese the singleton through that class method

**Consequences:**
* _Benefits_: Controlled access, reducing problems with program namespace, can be subclassed, can be modified to a fixed number of instances. 
* _Downsides_: can be difficult when multithreading. Can be difficult when unit testings

**Implementation Tips:** 
- Define a class variable holding the instance
- Checks if instance exists
- Make the constructor private or protected

## Problems with Patterns
See book Generative Programming: Methods, Tools, and Applications 1st Edition
- Object Schizophrenia
- Preplanning
- Problem Area: Traceability 

## Applying this to my work
Questions: 
- How many design patterns do I have in my toolbelt? 
- Can I, without looking them up, formally describe them and give the key features of each? 
- How many design patterns do I apply to a given problem when working? 
- The only way to learn them is to apply them