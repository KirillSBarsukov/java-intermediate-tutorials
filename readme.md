# Java Intermediate Tutorials 
:bowtie: Created by Rama

:point_right: Lesson 1  : Recursion<br />
:point_right: Lesson 2  : Collections And ArrayList<br />
:point_right: Lesson 3  : LinkedList<br />
:point_right: Lesson 4  : List to Array<br />
:point_right: Lesson 5  : Collections sorting and replacing<br />
:point_right: Lesson 6  : Collections Copy and Fill<br />
:point_right: Lesson 7  : Frequency and Disjoint<br />
:point_right: Lesson 8  : Stacks, push, pop<br />
:point_right: Lesson 9  : Queue<br />
:point_right: Lesson 10 : HashSet<br />
:point_right: Lesson 11 : Generic Methods<br />
:point_right: Lesson 12 : Implementing Generic Methods<br />
:point_right: Lesson 13 : Generic Return Types<br />
:point_right: Lesson 14 : Part 1 - Threads<br />
:point_right: Lesson 14 : Part 2 - Threads Call<br />

## Object Oriented Programming
	A - Abstraction
	P - Polymorphism
	I - Inheritance
	E - Encapsulation
	
------	
####ABSTRACTION 
* Focus on essentials/idea rather than specific details/events
* Ignore the irrelevant or unimportant

**Abstract Class**
* May or may not contain abstract methods (Eg- method without body: ```public void get();```  )
* But, if a class have at least one abstract method, then the class must be declared abstract.
* If a class is declared abstract it cannot be instantiated.
* To use an abstract class you have to inherit it from another class, provide implementations to the abstract methods in it.
* If you inherit an abstract class you have to provide implementations to all the abstract methods in it

:point_right: Lesson 15 : Abstract Class<br />
	A class which extends an abstract class and defines every method in it is called concrete class 

**Abstract Method**

:point_right: Lesson 16 : Abstract Method<br />

------
####POLYMORPHISM 
* Many Forms/Behaviour
* It is of two types
	* Static Binding - Compile time polymorphism 
		* Eg: Method Overloading
	* Dynamic Binding - Runtime polymorphism
		* Eg: Method Overridding

**Method Overloading**
* Same Method name
* Different parameter
* Different behavior

:point_right: Lesson 17 : Method Overloading <br />

**Method Overriding**
* Same Method name
* Same parameter
* Different class

:point_right: Lesson 18 : Method Overriding <br />

**Constructor Overloading**
* Same Constructor
* Different parameter

:point_right: Lesson 19 : Constructor Overloading <br />

------
####INHERITANCE 
* Code reuse - efficient method
* One class acquires the properties (methods and fields) of another Class
* ```extends``` is the keyword used to inherit the properties of a class

:point_right: Lesson 20 : Polymorphism <br />

------
####ENCAPSULATION 
* Process of wrapping code and data together into a single unit
* Variables of a class is hidden from other classes, and can be accessed only through the methods of their current class [Data hiding]
* To achieve encapsulation in Java
	* Declare the variables of a class as private.
	* Provide public setter and getter methods to modify and view the variables values.
* Benefits
	* The fields of a class can be made read-only or write-only
	* It provides you the control over the data

:point_right: Lesson 21 : Encapsulation <br />

------
####INTERFACE 
* Collection of abstract methods
* Writing an interface is similar to writing a class. But a class describes the attributes and behaviors of an object. And an interface contains behaviors that a class implements.
* How it varies from a class
	* You cannot instantiate an interface
	* An interface does not contain any constructors
	* All of the methods in an interface are abstract(by default its public abstract)
	* An interface can extend multiple interfaces

:point_right: Lesson 22 : Interface <br />

------
:point_right: Lesson 23 : Final Keyword <br />
* Example for variable, method and class

:point_right: Lesson 24 : Anonymous Class and Object <br />

Added Collections tutorial
