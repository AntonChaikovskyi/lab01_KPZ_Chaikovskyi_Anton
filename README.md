#  Laboratory Work 1: Principles of Programming in C#
#  Description
This project implements a zoo management system using the C# programming language. The project contains classes that correspond to animals, enclosures, food, employees, and zoo inventory.

## Adherence to Programming Principles

1. Single Responsibility Principle
Each class in the project is responsible for only one specific area of functionality:

- ** Animal: Represents information about animals.
- ** Enclosure: Responsible for enclosures in the zoo.
- ** Food: Represents information about food.
- ** ZooKeeper and Veterinarian: Employee classes, each of which is responsible for different roles in the zoo.
- ** Inventory: Manages the zoo’s inventory.

2. Open/Closed Principle
The classes in the project are designed to be open for extension but closed for modification. For example, new subclasses of animals or new types of food can be easily added without changing the main logic of the Inventory class.

3. Liskov Substitution Principle
The Mammal and Reptile subclasses can be used anywhere an Animal class object is expected, without violating the rules of correct program operation.

4. Interface Segregation Principle
Although there is no explicit use of interfaces in this code, the concept can be applied by separating functionality into separate interfaces for different types of animals, enclosures, and other zoo equipment.

5.  Dependency Inversion Principle
Constructors and properties are used in the code to introduce dependencies. For example, the Inventory class receives data about animals, enclosures, food, and employees through the constructor, allowing these data to be changed without changing the Inventory class itself.

This project adheres to the basic principles of object-oriented programming, ensuring its flexibility and extensibility.