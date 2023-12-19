# Coding Guidelines

When making code changes and reviewing a PR with code changes, try to keep the following principles in mind:

- **DRY** - Don't repeat yourself. If you see repeated code, suggest a way to [refactor](https://refactoring.guru/refactoring/techniques) it.
- **KISS** - Keep it simple, stupid. If you see overly complex code, suggest a way to simplify it.
- **YAGNI** - You aren't gonna need it. If you see code that is not required, suggest a way to remove it.
- **SOLID** - The SOLID principles are 5 principles that make code more understandable, flexible, and maintainable. If you see code that violates any of the principles, suggest a way to [refactor](https://refactoring.guru/refactoring/techniques) it.
  - **Single responsibility principle** - A class should have one, and only one, reason to change.
  - **Open/closed principle** - You should be able to extend a class's behaviour without modifying it.
  - **Liskov substitution principle** - Derived classes must be substitutable for their base classes.
  - **Interface segregation principle** - Make fine-grained interfaces that are client-specific.
  - **Dependency inversion principle** - Depend on abstractions, not concretions.
- **GRASP** - The GRASP principles are a set of principles that provide guidelines for assigning responsibilities to classes and objects in object-oriented design. If you see code that violates any of the principles, suggest a way to [refactor](https://refactoring.guru/refactoring/techniques) it.
  - **Information expert** - Assign respon­sib­ility to the class that has the inform­ation needed to fulfill it.
  - **Creator** - Assign creation respon­sib­ility to the class that has relation­ships with the required objects, or has the inform­ation needed to create them.
  - **Protected variations** - Identity code that might change behaviour based on external factors.
  - **High cohesion** - A class's responsibilities should be strongly related and focused on providing a well-defined service.
  - **Low coupling** - A class should avoid being tightly coupled to other classes.
  - **Pure fabrication** - Do not confuse the responsibilities of classes modelling real domain concepts with classes representing artificial concepts—for example, ShoppingCart vs. ShoppingCartService, where the latter is a pure fabrication.
  - **Polymorphism** - Use polymorphism over conditional logic when dealing with different types of objects.
  - **Controller** - Use controller classes to delegate work to other classes.
  - **Indirection** - Introduce mediating classes to decouple other classes when the design demands it.
- **LoD** - The Law of Demeter is a principle of software development that states that a software module should not know about the innards of the objects it manipulates but only know about the objects it manipulates directly. If you see code that violates this principle, suggest a way to [refactor](https://refactoring.guru/refactoring/techniques) it.
- **PIT** - Prefer Isolated Tests. If you see tests that depend on other tests, suggest a way to [refactor](https://refactoring.guru/refactoring/techniques) it.
- **SLAP** - Single Level of Abstraction Principle. If you see code that mixes high-level concepts with low-level details, suggest a way to [refactor](https://refactoring.guru/refactoring/techniques) it.

*Please add more coding principles to this list if you feel that they are missing.*
