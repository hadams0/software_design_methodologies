# Software Methodologies

## Q1

Coupling refers to the communication between different modules, and cohesion referes to the grouping of all functionally related elements. A high level of cohesion would signify that the elements are closely related and serve a single purpose, whereas low cohesion means the elements are loosely related and serve multiple purposes. A good structured design would have high cohesion and low coupling arrangements.

## Q2

In the top-down approach, a process called modulisation occurs, where complex algorithm is broken down into smaller fragments, better known as ‘modules.’ These modules are then further broken down into smaller fragments until they can no longer be fragmented. In bottom-up programming, the modules are designed individually and are then integrated together to form a complete algorithmic design. The bottom-up approach best describes function orientated design as it identifies the small chunks of the problem and solves it moving its way to the top.

## Q3

Class diagrams are most useful in Object Orientated Programming as they can be mapped directly with object-oriented languages.

## Q4

Abstraction expresses the intent of the class rather than the actual implementation.

Ecapsulation is the mechanism of hiding of data implementation by restricting access to public methods.

Static polymorphism is achieved using method overloading and dynamic polymorphism using method overriding.

Inheritance expresses “is-a” and/or “has-a” relationship between two objects.

## Q5

The Strategy Pattern is a design approach that helps to change the behaviour of a program by switching between different algorithms or strategies. It is a way to vary a family of encapsulated algorithms that enable a class behaviour or it's algorithm to change during run time.

In an object-oriented system, a different class would be created for each strategy, while in a functional system, functions or lambdas would be used to represent the strategies, but both ways allow the program to be flexible and adaptable.

## Q6

I would use the OOD method to create the new online payment system. This method gives the greatest level of reuseability and flexibility, as functions would be able to be resued or extended without the need to modify or change the existing code. Furthermore, the function of the payment method could be used throughout buying a new coat or ordering a takeaway, by creating separate classes for each payment method, to allow it to handle different payment scenarios without duplication, and by adapting the strategy pattern.
