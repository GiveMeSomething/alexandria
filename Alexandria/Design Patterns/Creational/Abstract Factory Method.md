*Oh my, another layer of abstraction*

## Problems
- The `Abstract Factory method` solves the same problems as [[Factory Method]], but with one extra scenario
	- How can families of related or dependent objects be created?[(1)](#references)
- [[Factory Method]] solve the problem of creating an independent product, but there are cases where objects must go in a specific group to make sense, where multiple `factory method` is not really optimal
- **Creating objects directly within a class that requires the objects is inflexible because it commits the class to that particular objects, making it impossible to change the instantiation later independently**[(1)](#references)

## Intent
- Produce families of related objects without specifying their concrete classes[(2)](#references)

## Structure
[[Abstract Factory Method Illu]]

## Pros and Cons

[[Factory Method#Pros and Cons]]

### Pros
- Ensure that products getting from a factory are compatible with each other, if there are needs where only products in a family can work together

### Cons
- This will further increase code complexity compared to factory method since we have to introduce another layer of abstraction above factory


## References
1. https://en.wikipedia.org/wiki/Abstract_factory_pattern
2. https://refactoring.guru/design-patterns/abstract-factory