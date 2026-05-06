# **Core Concepts: OOP and SOLID in TypeScript**

### **The Four Pillars of Object-Oriented Programming (OOP)**

The foundational pillars of OOP provide the structure necessary for modular and reusable code in TypeScript. 1

* **Encapsulation:** The practice of bundling data and methods within a class while using access modifiers (private, protected, public) to restrict direct access to the internal state, ensuring data integrity. 3  
* **Abstraction:** Reducing complexity by hiding internal implementation details and exposing only essential features, typically achieved through abstract classes or interfaces. 5  
* **Inheritance:** A mechanism that allows a subclass to acquire the properties and methods of a superclass, facilitating code reuse and the creation of hierarchical relationships. 1  
* **Polymorphism:** The ability of different objects to respond to the same method call in unique ways, often through method overriding (runtime) or overloading (compile-time). 5

### **The SOLID Principles**

These five principles are designed to make software more maintainable, flexible, and scalable. 2

* **Single Responsibility Principle (SRP):** A class should have only one reason to change, meaning it should focus on a single piece of functionality or responsibility. 8  
* **Open/Closed Principle (OCP):** Software entities should be open for extension (adding new behavior) but closed for modification (altering existing code). 11  
* **Liskov Substitution Principle (LSP):** Objects of a superclass should be replaceable with instances of their subclasses without affecting the correctness or behavior of the program. 4  
* **Interface Segregation Principle (ISP):** Clients should not be forced to depend on methods they do not use; this favors creating several small, specific interfaces over one large, general-purpose interface. 6  
* **Dependency Inversion Principle (DIP):** High-level modules should depend on abstractions (interfaces) rather than low-level modules (concrete implementations).

### **Key TypeScript Implementation Tools**

* **Interfaces vs. Abstract Classes:** Interfaces act as purely structural contracts for "duck typing" and have no runtime overhead. Abstract classes can provide shared implementation and exist at runtime, allowing for type checking via instanceof. 14  
* **Dependency Inversion (DIP) vs. Dependency Injection (DI):** DIP is the overarching architectural principle of depending on abstractions. 6 Dependency Injection is the technical pattern used to implement DIP by "injecting" required dependencies into a class from an external source. 17

#### **Works cited**

1. Four pillars of Object-Oriented Programming in TypeScript, accessed on May 5, 2026, [https://content.techgig.com/career-advice/mastering-object-oriented-programming-in-typescript-the-four-pillars-explained/articleshow/123467510.cms](https://content.techgig.com/career-advice/mastering-object-oriented-programming-in-typescript-the-four-pillars-explained/articleshow/123467510.cms)  
2. SOLID \- Wikipedia, accessed on May 5, 2026, [https://en.wikipedia.org/wiki/SOLID](https://en.wikipedia.org/wiki/SOLID)  
3. Request: 4 pillars of OOP & meanings : r/Rightytighty \- Reddit, accessed on May 5, 2026, [https://www.reddit.com/r/Rightytighty/comments/10rm22f/request\_4\_pillars\_of\_oop\_meanings/](https://www.reddit.com/r/Rightytighty/comments/10rm22f/request_4_pillars_of_oop_meanings/)  
4. The Four Pillars of Object-Oriented Programming in TypeScript \- DEV Community, accessed on May 5, 2026, [https://dev.to/coder7475/the-four-pillars-of-object-oriented-programming-in-typescript-1mf9](https://dev.to/coder7475/the-four-pillars-of-object-oriented-programming-in-typescript-1mf9)  
5. Object-Oriented Programming (OOP): Understand the 4 Pillars with Clear Examples, accessed on May 5, 2026, [https://dev.to/paulocappa/object-oriented-programming-oop-understand-the-4-pillars-with-clear-examples-3bci](https://dev.to/paulocappa/object-oriented-programming-oop-understand-the-4-pillars-with-clear-examples-3bci)  
6. SOLID Principles in TypeScript — A Complete, Practical Guide with Real Examples, accessed on May 5, 2026, [https://medium.com/@navidbarsalari/solid-principles-in-typescript-a-complete-practical-guide-with-real-examples-83f25e093bdf](https://medium.com/@navidbarsalari/solid-principles-in-typescript-a-complete-practical-guide-with-real-examples-83f25e093bdf)  
7. (PDF) The Impact of SOLID Principles on Code Quality and Software Lifecycle, accessed on May 5, 2026, [https://www.researchgate.net/publication/393182833\_The\_Impact\_of\_SOLID\_Principles\_on\_Code\_Quality\_and\_Software\_Lifecycle](https://www.researchgate.net/publication/393182833_The_Impact_of_SOLID_Principles_on_Code_Quality_and_Software_Lifecycle)  
8. TypeScript Tales: Unraveling Abstracts and Interfaces \- DEV Community, accessed on May 5, 2026, [https://dev.to/bilelsalemdev/typescript-tales-unraveling-abstracts-and-interfaces-3bhf](https://dev.to/bilelsalemdev/typescript-tales-unraveling-abstracts-and-interfaces-3bhf)  
9. Software Architecture: Mastering S.O.L.I.D Principles with Practical ..., accessed on May 5, 2026, [https://levelup.gitconnected.com/software-architecture-mastering-s-o-l-i-d-principles-with-practical-examples-in-typescript-b4932f772920](https://levelup.gitconnected.com/software-architecture-mastering-s-o-l-i-d-principles-with-practical-examples-in-typescript-b4932f772920)  
10. Applying SOLID Principles in TypeScript | CodeSignal Learn, accessed on May 5, 2026, [https://codesignal.com/learn/courses/applying-clean-code-principles-1/lessons/applying-solid-principles-in-typescript](https://codesignal.com/learn/courses/applying-clean-code-principles-1/lessons/applying-solid-principles-in-typescript)  
11. SOLID Design Principles Every JavaScript and TypeScript Developer Should Know \- Strapi, accessed on May 5, 2026, [https://strapi.io/blog/solid-design-principles-javascript-typescript-guide](https://strapi.io/blog/solid-design-principles-javascript-typescript-guide)  
12. SOLID Principles in JavaScript & TypeScript — Real-World Examples You Can Actually Use, accessed on May 5, 2026, [https://javascript.plainenglish.io/solid-principles-in-javascript-typescript-real-world-examples-you-can-actually-use-4979229999ed](https://javascript.plainenglish.io/solid-principles-in-javascript-typescript-real-world-examples-you-can-actually-use-4979229999ed)  
13. Applying SOLID Principles in JavaScript and TypeScript Framework \- DEV Community, accessed on May 5, 2026, [https://dev.to/wafa\_bergaoui/applying-solid-principles-in-javascript-and-typescript-framework-2d1d](https://dev.to/wafa_bergaoui/applying-solid-principles-in-javascript-and-typescript-framework-2d1d)  
14. Clean Code with Multiple Classes in TypeScript: Interfaces and Abstract Classes | CodeSignal Learn, accessed on May 5, 2026, [https://codesignal.com/learn/courses/clean-code-with-multiple-classes-2/lessons/clean-code-with-multiple-classes-in-typescript-interfaces-and-abstract-classes](https://codesignal.com/learn/courses/clean-code-with-multiple-classes-2/lessons/clean-code-with-multiple-classes-in-typescript-interfaces-and-abstract-classes)  
15. What is the difference between interface and abstract class in Typescript? \- Stack Overflow, accessed on May 5, 2026, [https://stackoverflow.com/questions/50110844/what-is-the-difference-between-interface-and-abstract-class-in-typescript](https://stackoverflow.com/questions/50110844/what-is-the-difference-between-interface-and-abstract-class-in-typescript)  
16. Dependency Inversion VS Dependency Injection | by Shehan Vanderputt \- Medium, accessed on May 5, 2026, [https://medium.com/@stanislousvanderputt/dependency-inversion-vs-dependency-injection-35e0bf47510a](https://medium.com/@stanislousvanderputt/dependency-inversion-vs-dependency-injection-35e0bf47510a)  
17. Understanding the dependency inversion principle (DIP ..., accessed on May 5, 2026, [https://blog.logrocket.com/dependency-inversion-principle/](https://blog.logrocket.com/dependency-inversion-principle/)  
18. Inversion of Control Containers and the Dependency Injection pattern, accessed on May 5, 2026, [https://martinfowler.com/articles/injection.html](https://martinfowler.com/articles/injection.html)