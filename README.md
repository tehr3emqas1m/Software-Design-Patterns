#  Software Design Patterns Repository

![Static Badge](https://img.shields.io/badge/Creational_Design_Patterns-red) 
![Static Badge](https://img.shields.io/badge/Structural_Design_Patterns-gray) 
![Static Badge](https://img.shields.io/badge/Behavioural_Design_Patterns-blue)

>  *Design Patterns are proven solutions to recurring software design problems. This repository contains Python implementations of the most common design patterns categorized by type.*

![Design Patterns Illustration](https://github.com/user-attachments/assets/ce8c7fc7-58f8-4660-bcdd-43a0de4e6a44)

---

##  Creational Design Patterns
Creational patterns deal with **object creation mechanisms**, aiming to create objects in a manner suitable to the situation.

###  Key Patterns
- **Singleton** – Ensures a class has only one instance and provides a global point of access to it.
- **Factory Method** – Defines an interface for creating an object, but lets subclasses decide which class to instantiate.
- **Abstract Factory** – Produces families of related objects without specifying their concrete classes.
- **Builder** – Separates the construction of a complex object from its representation.
- **Prototype** – Creates new objects by copying an existing object (prototype).

---

##  Structural Design Patterns
Structural patterns are concerned with **how classes and objects are composed** to form larger structures while keeping them flexible and efficient.

###  Key Patterns
- **Adapter** – Allows incompatible interfaces to work together.
- **Bridge** – Decouples an abstraction from its implementation so that the two can vary independently.
- **Composite** – Composes objects into tree structures to represent part-whole hierarchies.
- **Decorator** – Adds new behaviors to objects dynamically.
- **Facade** – Provides a unified interface to a set of interfaces in a subsystem.
- **Proxy** – Provides a surrogate or placeholder for another object.

---

##  Behavioral Design Patterns
Behavioral patterns are all about **object interaction and responsibility delegation**.

###  Key Patterns
- **Strategy** – Enables selecting an algorithm’s behavior at runtime.
- **Observer** – Allows objects to be notified of state changes in other objects.
- **Command** – Encapsulates a request as an object.
- **State** – Allows an object to alter its behavior when its internal state changes.
- **Mediator** – Reduces coupling between components by introducing a mediator object.
- **Iterator** – Provides a way to access elements of a collection without exposing its structure.

---

##  Repository Structure
All codes are in the Python_codes folder with the initial Alphabet i.e., C, S and B indicating the category that the pattern belongs to.
.
├── creational/
│   ├── singleton.py
│   ├── factory_method.py
│   └── ...
├── structural/
│   ├── adapter.py
│   ├── facade.py
│   └── ...
├── behavioral/
│   ├── state.py
│   ├── observer.py
│   └── ...
