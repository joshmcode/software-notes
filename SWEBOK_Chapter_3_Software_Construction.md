# SWEBOK Chapter 3 Software Construction
page 66 - 81

## Introduction 
Software construction is closely linked to a number of other knowledge areas (KAs) including Software Design, Software Testing, Software Configuration Management, Software Quality, Computing Foundations, as well as project management. 

## Topics for Software Construction

### Software Construction Fundamentals
There are five main areas of software construction: 
- **Minimizing complexity**: Due to people's inability to hold complex structures in working memory, the need for writing code that is clear and readable and simple (rather than clever), is the core of this idea.

- **Anticipating Change**: The environment will change, requirements will change, etc., so software must be built in anticipation of this change. 

- **Construction for Verification**: Software should be built to be tested by automated test suites, testing engineers, reviewed in code reviews, and tested by customers. Therefore, it should follow coding standards, support automated testing, and restrict the use of complex language structures. 

- **Reuse**: Resuse of software (COTS, components, source code, libraries, modules, plugins, etc.) can provide significant increase in quality and reduction in costs. Two closely related ideas are "construction for reuse" and "construction with reuse." 

- **Standards in Construction**: These include both internal and external standards and cover a wide range of areas such as communication methods, coding standards, platforms and tools. Additionally, much of this might be dictated by outside groups such as IEEE or internal, self-organizing groups. 

### Managing Construction
**Construction Life Cycle Models**: The choice of the life cycle model can dictate exactly what "construction" means. For sure, construction relates to coding, but if a life cycle model of agile,for example, is selected, then the construction KA may include design and testing as well. In the traditional waterfall approach this would not be the case, with most of the design happening early on. 

**Construction Planning**: Construction planning defines the order in which components are integrated, will impact how the team is able to reduce complexity and anticipate change, and determines to what degree prerequisites to construction are performed. 

**Construction Measurement**: Measures such as code written, code reused, faults, etc. can be used in the actual management of construction to ensure goals and objectives are being met. 

### Practical Considerations
Due to the chaos of the real world, construction is perhaps the most craftlike of all the KAs. 

**Construction Design**: similar to how construction workers must make on-demand design decisions when gaps in the designer's forethought are found, software engineers must also make such decisions.  

**Construction Languages**: Languages can be broken down into the categories of configuration, toolkit, scripting, and programming. Programming languages themselves use three types of notatino: linguistic (Java), formal (Event-B), and visual (MatLab).

**Coding**: Techniques for coding include the following:
- Techniques for creating understandable source code, including conventions and source code layout. 
- Useage of classes, etc. 
- Use of control structures
- Error handling
- Security
- Resource usage (locks, threads)
- Source code organization (packages, methods)
- Documentation
- Tuning

**Construction Testing**: 

### Construction Technologies

### Software Construction Tools