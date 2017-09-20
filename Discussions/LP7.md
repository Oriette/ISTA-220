#### Oriette Ramos
#### Lesson Plan 07
#### ISTA-220
#### C#

1.	What is a class? According to the book, what does a class ”arrange?"
A class arranges information and behavior into a meaningful entity.
2.	What are the two purposes of encapsulation?
The two purposes of encapsulation are:
i.	To combine methods and data within a class; in other words, to support classification.
ii.	To control the accessibility of the methods and data; in other words, to control the use of the class.
3.	How do you instantiate an instance of a class? How do you access that instance?
To instantiate an instance of a class, you create a variable specifying the class as its type, and then you initialize the variable with some valid data. For example, Homework h; declares the variable h with Homework as its type. h = new Homework(); initializes a new instance of Homework and assigns it to the variable h. You access the instance by calling the variable it is assigned to (h in this example).
4.	What is the default access of the fields and methods of a class? How do you change the default?
By default, the fields and methods of a class are private and inaccessible to code outside the class, but you can use the public keyword to expose fields and methods to the outside world.
5.	What is the syntax for writing a constructor?
The syntax for writing a constructor is a public method that does not return a value (not even void) and has the same name as the class. For example, the constructor with no parameters for the Homework class would look like: public Homework()
6.	What is the difference between class fields and methods, and instance fields and methods? How do you create class fields and methods?
Class fields and methods provide a useful function that is independent of any specific class instance. If you declare a method or a field as static, you can call the method or access the field by using the name of the class. No instance is required.
7.	How do you bring a static class in scope? Why would you want to bring a static class in scope?
Static using statements enable you to bring a class into scope and omit the class name when accessing static members. They operate in much the same way as ordinary using statements that bring namespaces into scope. This could be helpful if static methods from a specific class are called often throughout the code (like Math.Sqrt or Math.PI)
8.	Can you think of a good reason to create an anonymous class? What is it?
An anonymous class is a class that does not have a name. Anonymous classes can be useful when using query expressions.
9.	What is polymorphism as this term is used in computer science? This is not in the book.
Polymorphism is often referred to as the third pillar of object-oriented programming, after encapsulation and inheritance. Polymorphism is a Greek word that means "many-shaped" and it has two distinct aspects:
i.	At run time, objects of a derived class may be treated as objects of a base class in places such as method parameters and collections or arrays. When this occurs, the object's declared type is no longer identical to its run-time type.
