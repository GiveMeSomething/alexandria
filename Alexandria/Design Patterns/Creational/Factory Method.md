Also known as **Virtual Constructor**

## Problems
- The Factory Method design pattern solves problems like: [(2)](#references)
	-  How can an object be created so that subclasses can redefine which class to instantiate?
	-  How can a class defer instantiation to subclasses?
- Patterns
	- Classes that have (almost) the same way of working can be grouped using abstraction, in this case, a `factory method`
	- Object creation may scatter around your project, making tight coupling between your code and the class. With `factory method`, it can be group in one place, making it easier to make changes and avoid tight coupling
	- Separate product construction code from the code that actually use the product[(4)](#references)


## Intent

- Should be considered as an alternative to constructors - mostly when constructors aren't expressive enough [(1)](#references)

- Creating objects without having to specify the exact class of the object that will be created [(2)](#references)


## Structure

- [[Factory Method Illu]]

> "Define an interface for creating an object, but let subclasses decide which class to instantiate. The Factory method lets a class defer instantiation it uses to subclasses."
> [(3)](#references)


## Pros and Cons

### Pros

- *Single Responsibility Principle*. By moving all creation code to one place
- *Open/Closed Principle*. Easily support new class just by extend current abstract class, or implement current interface (for `Product`)
- *Avoid tight coupling*

### Cons
- The code become more complicated after implement this pattern as we have to create abstraction for Product and factories for creating types of product


## References
1. https://stackoverflow.com/questions/69849/factory-pattern-when-to-use-factory-methods
2. https://en.wikipedia.org/wiki/Factory_method_pattern
3. https://en.wikipedia.org/wiki/Design_Patterns
4. https://refactoring.guru/design-patterns/factory-method
