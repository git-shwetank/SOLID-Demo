# SOLID-Demo
To demonstrate the purpose of SOLID principles in Software Development

S - Single Responsibility

O - Open to Extension / Closed for Modification

L - Liskov's Substitution Principle

I - Interface Segregation Principle (ISP)

D - Dependency Inversion Principle (DIP)

Take aways-
- Keep the class as simple as possible with a single responsibility or behavior perfected in implementation.
- An existing concrete class definition should not be modified when need to add new implementation
- Ensure that every **derived class** can be used in place of **base class** (A Square sub class can not hold a Liskov's substitution non-compliant super class Rectangle as a rectangle instance may have different values of width and height)
- Functional seggregation should be done on interface levels to reduce generalisations and enhance objectivity. This reduces readibility by removing confusing methods away, hereby reducing changes of human error and misinterpretations.
- Use Abstraction to define concepts. The concepts may be implemented in different fashion or ways but the concept remains constant. When in practice _dependency_ shall be **how** concept is implemented in a situation. Any dependency of abstraction may be choosen independent of abstraction and without affecting other parts or actors or classes of the code.
  
