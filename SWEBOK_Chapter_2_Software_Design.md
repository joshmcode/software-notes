# SWEBOK Chapter 2 Software Design
Page 50-63

## Introduction
Software design can be viewed as both an activity and a result. 
- Software design as an activity: it is the part of the software engineering life cycle in which software requirements are analyzed in order to produce a description of the software's internal structure. 
- Software design as a result: it describes the software architecture and the interfaces between its decomposed components. 

There are two levels of design: software architectural design (e.g. "high-level design") and sftware detailed design. The latter is the specification of each component at a detailed level sufficient to facilitate its construction. 

## Breakdown of Topics for Software Design
### Software Design Fundamentals
In general, software design can be viewed as problem solving. 

To understand software design, we must understand how it fits into the software development cycle and understand those other areas of the cycle (like requirements analysis).

Software Design Principles:
> Principle: “a comprehensive and fundamental
law, doctrine, or assumption”

Here is a list of software design principles
- Abstraction
- Coupling and Cohesion
- Decomposition and modularization
- Encapsulation and information hiding
- Separation of interface and implementation
- Sufficiency, completeness, and primitiveness
- Separation of concerns

### Key Issues in Software Design
Quality in software is always a concern. Also, how to package, decompose and organize components. 

The above areas are relevant to all software. However, other areas are not directly in the application domain but are still relevant: 
- Concurrency (threading, multiple processes, tasks, etc.)
- Control and Handling of Events
- Data Persistence
- Distribution of Components
- Error and Exception Handling and Fault Tolerance
- Interaction and Presentation (this is _not_ User Interface Design, discussed later)
- Security

### Software Structure and Architecture
In the strictest sense, software architecture defines the elements that allows reasoning about a system, its components, and interactions among the components. 

In practice, however, software architecture is a broader discipline that studies a more abstract way of looking at structures and architectures.

High-level faces of software design can be called "views." Example views include:
- logical views (functional requirements)
- physical view (distribution issues)
- development view (how design is broken down into units)

**Architectural styles** is a specialization of relationships and element types, along with constraints for each of these. Examples:
- General: layers, pipes
- Distributed systems: brokers, client-server
- Interactive systems: model-view-controller
- Adaptable systems: reflection, microkernel
- Others: interpreters, rule-based, (AI??)

**Design patterns** is "a common solution to a common problem in a given context." What is the difference between design patterns and architectural patterns? Design patterns really go into the details. In other words, how to explicitely solve this common problem. Architecture patterns are higher-level patterns of software component/modules/system organization. Examples of design patterns:
- Creational pattern
- Structurel patterns
- Behavioral patterns

Because of the profound impact design choices make on the end result, it is helpful to think of the design process as a series of decisions instead of an activity. 

Finally, it can be useful to organize software around the concept of "product lines" which is software designed in a resuable manner with customizable components. Additionally, in OO programming there is the idea of a "framework" which is a partically completed core component that can be extended in functionality through the likes of plugins or modules. 

### User Interface Design


### Software Design Quality Analysis and Evaluation
### Software Design Notations
### Software Design Strategies and Methods
### Software Design Tools


