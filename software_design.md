# Software Design Methodologies

## Introduction

There is no single correct way to approach a software engineering problem. Designing a product which satisfies a customer's needs while leveraging a team's skillset (and delivering on time and on budget) isn't something with a one-size-fits-all solution. There is, however, usually one option which is a better fit for a given situation than others. In this exercise we will find out about some of the different ways in which we could go about designing a system.

## Design Strategies

There are three principle design strategies used in software engineering:

- Structured design
- Function oriented design
- Object oriented design

None of these are compulsory when designing a product but following one will greatly aid the process. Each has its benefits and each has its drawbacks. Unlike many other aspects of software engineering they generally exist in isolation as the principles of each sit in direct opposition to each other in some scenarios.

There is no scenario where one of these strategies _can't_ be used, but we may be making our lives harder by choosing one over another. Likewise the majority of programming languages can be used with any strategy, but some are better fits for one strategy than another. For example Java is an excellent choice for an object oriented design while Scala would be a better choice for a functional design. Some languages such as Python can be used effectively with either, but have to sacrifice some features to achieve that flexibility.

Within each methodology there are various **design patterns** which provide further structure for us. In general though these are much more easily transferred across methodologies, although the precise implementation will vary by language. In practice the language used for a project will likely be the last thing to be chosen, determined by a combination of methodology and design pattern.

## Task

In this exercise you will be required to research the design strategies listed above and answer some questions about them. Your answers should be in a markdown (`.md`) file and uploaded to GitHub, then the link submitted using the lab submission form. There is no MVP/extension split for this task - you should attempt to answer every question. You can collaborate with others in the cohort on the research part of the task but everyone should submit their own answers.


1. What do we mean by **coupling** and **cohesion** when discussing structured design?

In software engineering structured design involves breaking down largeer processes into smaller more manageable ones. This then increases clarity as well as design efficiency. Coupling measures the interdependece of two modules however cohesion on the other hand measures how the elements within the module interlink one another.

2. What is the difference between **top-down** and **bottom-up** design? Which best describes a function oriented design?

Top-down starts from resolving the more general larger problems to then breaking them down into more specific smaller scale issues. It is  Bottom-up on the the other hand works the opposite way by starting from the smaller scales problems and connecting them to resolve the higher level issue. 

Function oreinted design is where the model of the software design starts of with larger scale problems and is then broken down into a more manageable set of interacting units where there is better clarity in each unit identified. From the definitions stated above I can conclude that the top-down design would be the one that best describes function oreinted design.

3. In which design methodology would a **class diagram** be most useful?

A class diagram is a model used to present objects relationships with one another as well as their properties and methods. Class diagrams would be most useful in the bottom-up design methodology within object oreintated design as a top-down design would focus on the higher level aspects first and work through to the smaller scale aspects however a class diagram focuses on the smaller scale aspects and would therefore be better useful in bottom-up design as it's initial and main focus is on the smaller scale issues.

4. What are the **four pillars of object oriented programming**? Give a single-sentence description of each.

Encapsulation - includes the attributes/properties of the class as well as the methods. Through setting the date to private, public or protected, it restricts access to some sets of data contained by the object this then prevent any misconduct with data. 
Inheritance - the process by which one class can 'inherit' another class's properties and methods encouraging the use of code reusability.
Polymorphism -  where the same method is able to be used with different objects to complete different tasks. This enables the use of superclasses as well as the ability to have subclasses override. 
Abstraction - clear and concise way of only presenting neccesary data from object by not including complex implementation sets.

5. What is the **strategy pattern**? How would its implementation differ between a functional and object oriented system?

Strategy pattern is known as a behavioural design pattern this allows algorithms to be in a state where they are interchangeable.
Within object oreinted systems its implementation would involve having a class that refers to a strategy object and having methods to instruct algorithms to the strategy object. In functional oreinted systems the strategy pattern's implementation involves higher level functions and defining those functions for the strategys rather than defining classes.

6. Imagine your is creating a new online payment system. In order to gain maximum market share it can't be tied to a particular sector - it needs to work just as well when ordering a takeaway as when buying a new coat. Which design methodology would you suggest following? Give some justification for your decision.

When creating a new online payment system which has multiple purposes and functions the best design methodology that I would suggest would be the object oreinted approach with strategy pattern. This is as they have the ability to reuse code for different purposes and as they would allow for a wide range of different methods to be used such as using different payment methods making the online system more accommodating and flexible to customers.  


