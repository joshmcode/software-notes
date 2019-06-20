# P4L5 Design Principles

## Design Principles
Informal guidelines to be judicial applied in certain circumstances

(Informal piece of advice)

## Foundational Concepts First

### Coupling
The extent to which modules are dependent on each other. Low coupling (low dependence) is good. 

### Cohesion
The exten to which a module has a single purpose (i.e. "is it cohesive" as in an argument).

### Orthogonality
Exten to which the features of a system can be varied independently. 

### Information Hiding (encapsulation)
Exten to which implementation details of a system are hidden behind abstract interfaces. Inheritance can violate this principle.

## Principle Catalog
Note: these are guidelines

### Liskov Substitution Principles
Subclass instances, should satisfy parent-class constraints. 

### Law of Demeter
Suggest limits that on the classes that can be referred to by a given method. 

* Limits the objects that can be referred to
* Reduces coupling, but sometimes requires extra wrapper classes

### Hollywood Principle
The "don't call us, we'll call you" principle

### Dependency Inversion
High-level modules should not depend on low-level modules. 

### Open-Closed Principle
Open for extension but closes for modification. 

### Interface Segregation Principle
Suggests that clients depend on an interface to a part of the large class's features.

### Release Reuse Equivalency Principles
Granule of reuse should be the granule of release. Release highly cohesive code units. 

Classes that are not released together should not be grouped together. 

### Common Closure Principle
Packages the change together should be released together

### Dependency Structure Matrix
Boolean matrix in which rows and columns correspond to components. Lattix Tool

### Acyclic Dependency Principle
Dependencies between packages must not form cycles. 

How to fix this? Inject a middle-layer between A and B (C)

### Stability Principle
A module should not depend on packages that are more likely to change than it is. 

### Bad Smells
Code situations that are suggestive of design problems (things to avoid). For example: duplicate code. 

## Refactoring OsMowsis
How can I refactor my project? 

## Riel Heuristics

- Most of the methods defined on a class should be using most of the data members most of the time.
- Check constraints and constructors
- Do not change of state without going through an object's public interface (indicates we require getters and setts). 
- Distribute system intelligence horizontally as uniformly as possible (no god classes).

### Other things
- Single choice principles
- Transparency
- Intentionality

## Example: Composite Pattern
The purpose of this design pattern is summed up nicely in [Wikipedia:](https://en.wikipedia.org/wiki/Composite_pattern) 

## Resources
  1. Lattix
  2. Riel's Heruistics