
## Inheritance
- *"is a"* relationship + parent/child relationship. 
	- `Apple` is a `Fruit`
	- `Apple` is a child of `Fruit` (parent)
- There are two types of inheritance:
	- Class inheritance
	- Interface inheritance

## Composition
- *"part of"* relationship
	- `Tire` is a part of car
- Both class related in this relationship is interdependent to each other. Meaning that they won't make sense if one is made to standalone

## Association
- *"has a"* relationship
	- `Employee` has a `Manager` :v
- There are three types of association
	- One-to-one
	- One-to-many
	- Many-to-many
- Almost identical to composition, but classes in this relationship can exist on their own, without the each others dependency
- No entity working as a owner, as classes can have each other as dependency, without affecting the base class meaningfulness

## Aggregation
- Special form of [association](#association)
- **Aggregation** is a one-way association
- In aggregation, both classes meet for some operation, and then separated again
	- e.g. `Student` has a `Address`. But unlike association, an `Address` might not be related to any `Student`, so no vice versa.