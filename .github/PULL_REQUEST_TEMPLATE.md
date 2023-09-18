## Description

Description goes here...

Fixes `#issue-number, closes #issue-number`

## Checklist for the creator

- [ ] Ensure you have provided a clear and concise description.
- [ ] Ensure that the PR is labelled.
- [ ] Ensure `Closes` or `Fixes` are added to the PR description or commits so issues closed by this PR are correctly linked. An example is shown in the description.
- [ ] Ensure all `checks` pass before assigning the PR to a reviewer.
- [ ] Ensure that your changes maintain or improve test coverage.

## Checklist for reviewers

- [ ] Double-check that the creator has completed his checklist sufficiently.
- [ ] Provide constructive feedback on the PRs changes. Keep a focus on the solution approach, code quality, and that the PR solves a problem described in an issue.
- [ ] Check for any security vulnerabilities introduced by the PR or already present in the codebase touched by the PR.

---

## Guidelines

The following guidelines are meant to help you create better contributions and review contributions made by others. These guidelines are not rules but rather guidelines. There are always exceptions to the rules, and sometimes, it is better to break a rule than to follow it. Use your best judgment when creating or reviewing contributions.

### Coding Guidelines

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
