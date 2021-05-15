
## S.O.L.I.D Principle in Android

Basically, SOLID is one of the most significant acronyms in the Object Oriented Programming concepts. Using SOLID principles in Android development could be helpful and effective to follow clean code principles.

### What is the definition of SOLID?

SOLID is an acronym for five design principles in Object-Oriented software development intended to make software designs more understandable, flexible and maintainable. These five principles are described by Robert C. Martin. SOLID principles are briefly as follows:

* S — Single Responsibility Principle (known as SRP)
* O — Open/Closed Principle
* L — Liskov’s Substitution Principle
* I — Interface Segregation Principle
* D — Dependency Inversion Principle

### S — The Single Responsibility Principle (SRP):

> A class should have only one reason to change

The Single Responsibility Principle indicates that every class should have one and only one responsibility. In other words, if our class does more than one responsibility, we should split the functionalities and responsibilities in various classes. Therefore, this makes the class more robust.

### O — The Open-Closed Principle (OCP):

> Software entities such as classes, functions, modules should be open for extension but not modification.

This means that if we are required to add a new feature to the project, it is good practice to not modify the existing code but rather write new code that will be used by the existing code. 

### L —The Liskov Substitution Principle (LSP):

> Child classes should never break the parent class’ type definitions.

This principle indicates that parent classes should be easily substituted with their child classes without changing the behavior of software. It means that a sub-class should override the methods from a parent class, which does not break the functionality of the parent class.

### I — The Interface Segregation Principle (ISP):

> The interface-segregation principle (ISP) states that no client should be forced to depend on methods it does not use.

This means that if an interface becomes too fat, then it should be split into smaller interfaces so that the client implementing the interface does not implement methods that are of no use to it.

### D — The Dependency Inversion Principle (DIP):

> High-level modules should not depend on low-level modules. Both should depend on abstractions.
> Abstractions should not depend upon details. Details should depend upon abstractions.

This principle suggests that high level modules should not depend on low level. So, both should depend on abstractions. Furthermore, abstraction should not depend on details. Details should depend upon abstractions.</br>
If you use a class insider another class, this class will be dependent of the class injected.

---------------------------------------------------------------------------
For complete reference check followings,</br>
1. https://proandroiddev.com/exploring-s-o-l-i-d-principle-in-android-a90947f57cf0
2. https://medium.com/kayvan-kaseb/the-solid-principles-for-android-developers-75fd4ca3ef84
3. https://medium.com/android-news/android-development-the-solid-principles-3b5779b105d2

