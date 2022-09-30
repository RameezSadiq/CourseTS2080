Lecture 5 notes

Class Diagram
Describes the types of objects that can be created (object = instance of a class)
Attributes of the classes (attributes = the properties of a class/ variables)
Any variable that is bound in class (meaning = parameter of a constructer)
Operations of class that can occur
Relationships between these objects
 

Relationship between objects
A ---------------------- B  (Association: A and B call each other)

 
An association is a solid line between two classes, Directed from the source class to the target class.
Multiplicity indicates. 1 pilot can fly 10 planes.
Star means many.
Label it like 1 plane assigned to 2 pilots.

The multiplicity of a property is an indication of how many objects may fill the property. Lower bound and an upper bound are usually defined but not always.

Type A : 1(an order must have precisely one customer)
Type B: 0.1(A CORPORATE CUSTOMER MAY OR MAY NOT HAVE A SINGLE SALES REP)
Type C: *(A customer need not place an order, and there is no upper limit to the number of orders a customer may place – zero or more orders)

Aggregation and association is the same.
Aggregation in uml is meaningless

An abstract class is a particular type of class that cannot be instantiated.
An abstract class is designed to be inherited by subclasses that implement or override its methods.


Relationships between objects – b

A-------- B 
A____________>B Inheritance: A inherits from B. A “Is-a” B.
Inheritance and generalization is the same.
Composition: A has-an instance of B. B cannot exist without A.


