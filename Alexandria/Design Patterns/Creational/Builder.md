
## Problems
- Imagine a complex object with step-by-step initialization with multiple fields and parameters, each to create a different version of that object. This will probably have a huge constructor, making it hard to use.
	- `Builder` pattern abstract this instantiation process. All steps from the huge constructor now broken down into functions that represent the respective step
- We can use `Builder` pattern to solve problems like:
	- Abstract the instantiation process of a complex object, that requires many steps, or many parameters
	- To allow multiple representations for the object that's constructed, for each combination of steps, or parameters
- 

## Intent
- To separate the construction of complex object from its representation so that the same construction process can create different representations
- Key consequences when using `Builder` pattern
	- **It lets you vary a product's internal representation**
		- Provide outside a interface to work with, all information about the product's internal and how it's assembled are hidden
		- As clients are working with an interface, new kind of products can be introduce easily
	- **It isolates code for construction and representation**
		- Just like most of the Creational pattern
	- **It gives you fine control over the construction process**
		- No more complex constructor means that optional features for product can be more flexible, this still affect the `Builder` interface, and subsequently, all related class that currently implement the interface. (**Opinion**)

## Structure
[[Builder Illu]]




