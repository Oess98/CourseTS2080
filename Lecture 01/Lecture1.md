## What is object oriented programming?
- Object oriented programming is a programming concept. OOP offers a way to organize the code you write.
- Classes define methods and data that can be used to create objects.
- Classes can be organized hiearchly.
-  OOP is implemented in multiple languages, some noteable examples are: C++, Java, C# and Python. 


## What are the basic concepts of OOP?
- Template of data and functions. 
- Manipulating the code of data. 
- Classes that cover multiple things
- Re-usability
- Scaleable 



## What are the main principles of OOP?
- Inheritance
- Encapsulation
- Abstraction
- Polymorphism


## Encapsulation
- Encapsulation is a technique for restricting access to data. 
- Methods for getting and setting data is often used with encapsulation. These methods are often referred to as getters and setters.

### 3 types of encapsulation
- public
    - Access outside class
- private
    - Only access inside class
- protected
    - Access within class and subclasses
### Why use encapsulation
- Protect data that is should not be easily modifed.
- Security
    - Only provide getters and setters to data should be available
    - Add logic control to values. For example clamping.
- Simplicity
    - Only provide access to the data that is needed outside the class. 
- Aesthetics
    - Better readability.
    

## Abstraction
- Complex code hidden in classes. 
- Provides easy interface for usage.

## Inheritance
- Is when a class inherits from another class.
- Data, method declaration, method implementation can be inherited. 


## Polymorphism
- When an object can take multiple forms. 

If we have a class for cat which inherits from feline that inherits from animal. 

`Animal` -> `Feline` -> `Cat`

If we create an object with class `Cat`. The object can be both a `Feline` and `Animal`. In this way the object is polymorphic.  

