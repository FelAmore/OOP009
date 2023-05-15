# OOP Forum Week 9

### 1a. By making use of an example from the above scenario, distinguish between a class and an instantiation of a class.
#### A class is a blueprint that defines the properties and behaviors of objects, while instantiation is the process of creating an actual object from that blueprint.


### 1b. By giving two examples, explain how the principles of inheritance can be incorporated into the design of this administration program.
#### Ex1: Inheritance for Vehicle Hierarchy
To manage vehicles in an administration program for a transportation company, we can use a hierarchy where a base class called "Vehicle" holds shared details like make, model, and year. From there, you can create subclasses like "Car," "Motorcycle," and "Truck" which inherit the common properties and have their own unique attributes such as number of doors or cargo capacity.
#### Ex2: Inheritance for User Authentication
To manage user authentication in an administration program, we can use inheritance to create a hierarchy of user types. A base class called "User" can store common information like username and password. Derived classes like "AdminUser," "RegularUser," and "GuestUser" can be created to inherit from the User class. Each derived class can have unique methods and permissions tailored to their user type, such as admin privileges or the ability to view restricted content. Inheritance allows for easy management and distinction between user types, while reusing shared functionality from the base class.


### 1c. Describe how the use of libraries can facilitate the development of programs like this company’s administration program.
Using libraries in the development of a company's administration program simplifies the process by providing ready-made functions, enhancing functionality, promoting code reusability, and offering community support.
