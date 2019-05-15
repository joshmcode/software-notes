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
User design should optimize the control of the machine at the hands of the user. It should be design to "match the skills, experience, and expectations of its anticipated users."

Basic design principles of User Interface Design:
- Learnability
- User familiarity
- Consistency
- Minimal surprise
- Recoverability
- User guidance
- User diversity

User interface design tries to answer two main question: (1) how should the user interact with the software and (2) how should information be presented to the user. 

Common interaction techniques between users and computers include question and answer, direct manipulation, menu selection, for fill-in, command language, and natural language. 

When designing information presentation, it's good to keep this rule in mind: 
> A good design keeps the information presentation separate from the information itself (such as in the MVC model).

Other aspects of information presentation include load time and the useage of design aspects like color to indicate key information or the state of the application to the user. A good design tip is to avoid using too many color combinations and try to take visual impaired users into consideration.

There are three core activities in user interface design:
- user analysis
- software prototyping
- interface evaluation

If an application is going to be used in an international context, minimal change would be desired for changes in language and similar regional factors (like symbols)so the design should take this into consideration. 

The use of metaphors and conceptual models (like a trash can for "delete") can make the system easier to understand and interact with. When using a metaphor, don't use more than one representation for the same concept or users could become confused. 

### Software Design Quality Analysis and Evaluation
Attributes of quality can be broken down into... 

**Runtime discernable**: Performance, security, availability, functionality, usability

**Non-discernable at runtime**: modifiability, portability, reusability, testability

**Intrinsic qualities**: conceptual integrity, correctness, completeness

There are a number of techniques to evaluate quality, such as software design reviews, static analysis, simulation and prototyping. To measure the quality of a product, the design approach must be taken into consideration, but in general approaches can be broken up into **function based** and **object-oriented** approaches. 

### Software Design Notations

### Software Design Strategies and Methods

### Software Design Tools


