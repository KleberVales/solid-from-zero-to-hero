# solid-from-zero-to-hero

SOLID principles are five object-oriented programming principles that facilitate software development, 
making them easy to maintain and extend. These principles can be applied to any OOP language.

## The 5 principles of OOP

- S — Single Responsibility Principle
- O — Open-Closed Principle
- L — Liskov Substitution Principle
- I — Interface Segregation Principle
- D — Dependency Inversion Principle

These principles help programmers write cleaner code by separating responsibilities, reducing coupling, facilitating refactoring, and encouraging code reuse.

**1. SRP — Single Responsibility Principle:**

Single Responsibility Principle — A class should have one, and only one, reason to change.

This principle states that a class should be specialized in a single subject and have only one responsibility within the software; that is, the class should have a single task or action to perform.

When learning object-oriented programming, we unknowingly give a class more than one responsibility and end up creating classes that do everything — God Classes*. At first, this may seem efficient, but because responsibilities end up being mixed, when there is a need to make changes to this class, it will be difficult to modify one of these responsibilities without compromising the others. Every change ends up being introduced with a certain level of uncertainty in our system — especially if there are no automated tests!

Violating the Single Responsibility Principle can lead to several problems, including:

- Lack of cohesion — a class should not assume responsibilities that are not its own;

- High coupling — More responsibilities generate a higher level of dependencies, making the system rigid and fragile for changes;

- Difficulties in implementing automated tests — It is difficult to "mock" this type of class;

- Difficulties in reusing code;


The single responsibility principle is not limited to classes; it can also be applied to methods and functions. 
In other words, anything responsible for performing an action should only be responsible for what it is designed to do.

I consider SRP (Single Principle Ratio) one of the most important principles; it ends up being the basis for other principles and patterns because it addresses topics such as coupling and cohesion, characteristics that all object-oriented code should have.

By applying this principle, you will automatically be writing cleaner and more maintainable code! If you are interested in this subject, I recommend reading about best practices for writing impeccable code.

**2. OCP — Open-Closed Principle:**

Open-Closed Principle — Objects or entities should be open for extension but closed for modification; that is, 
when new behaviors and features need to be added to the software, we should extend and not modify the original source code.

**3. LSP— Liskov Substitution Principle:**

Liskov Substitution Principle — A derived class must be substitutable for its base class.

The Liskov substitution principle was introduced by Barbara Liskov in her 1987 lecture "Data Abstraction." Liskov's formal definition states that:

To avoid violating the Liskov Substitution Principle, in addition to structuring your abstractions very well, in some cases you will need to use dependency 
injection and also other SOLID principles, such as the Open-Closed Principle and the Interface Segregation Principle—which will be covered in the next topic.

Following the LSP allows us to use polymorphism with more confidence. We can call our derived classes by referring to their base class without worrying about unexpected results.








