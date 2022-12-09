- typical solutions to commonly occurring problems in software design
- general concept for solving a particular problem
- Said to be consisted of 4 main parts:
	- **Intent** of the pattern briefly describes both the problem and the solution.
	- **Motivation** further explains the problem and the solution the pattern makes possible.
	- **Structure** of classes shows each part of the pattern and how they are related.
	- **Code example** in one of the popular programming languages makes it easier to grasp the idea behind the pattern.

## Own definition
- Typical solution to solve **commonly occuring problems** (pattern) in **software design**, thus the name ***"Design Pattern"***

- Consist of 4 main parts:
	- **Intent**: What is/are the problem(s) are we trying to solve? Initial thoughts?
	- **Motivation**: How are we going to solve the problem? Using what we already have or something anew?
	- **Structure**: Solution to the problem, including detailed description
	- **Code example**

- Design patterns classification
	- This note following ***"Refactoring Guru"*** on how they classified patterns, specifically, by their **Intent**
	- This will cover three main groups of patterns:
		- Behavioral
		- Creational
		- Structural

> I like thinking about design pattens in terms of my classes being `people`, and the patterns are the ways that the people talk to each other. (2)


## How to select a Design Pattern*
- **Consider how design patterns solve design problems**
	- Different design patterns solve their own field of design problem, like helping you find the appropriate object, determine object granularity, specify object interface, etc...
- **Scan Intent sections**
	- Intent section of each design patterns show briefly what is the problem and how that pattern trying to solve that problem. It's a good start when trying to pick a design pattern
	- In some case, there are many patterns that solve the same problem, so try to scan through all the patterns before making the final pick
- **Study how patterns interrelate**
	- Can help direct you to the right pattern or group of patterns
- **Study pattern of like purpose**
	- Multiple design patterns have the same purpose, but different approach. It would be great if one can see the similarities and the differences between patterns of like purpose
- **Examine a cause of redesign**
	- Design pattern help you reuse and avoid redesign. Examine causes of redesign might give you insight of what pattern you should pick
- **Consider what should be variable in your design**
	- Variable in here is things that you might change, or easily affected by changes in requirement. Picking the right design patterns can help the changes happen easier


### References

1. https://refactoring.guru/design-patterns/what-is-pattern
2. https://stackoverflow.com/questions/69849/factory-pattern-when-to-use-factory-methods



