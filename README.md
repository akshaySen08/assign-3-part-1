# assign-3-part-1
Internet Computing Assignment 3

Steps to run the application:

1. Make sure you have Java installed on your computer.
2. Install eclipse, and editor for writing Java applications.
3. On the left hand side of the eclipse editor click on file option.
4. Select "open application folder from computer".
5. After selecting the folder, right click on the main folder visible on the left hand side work space of application.
6. Click on Run as -> Java Application.

----------------------------------------------------------------------------------------------------------------------------------

Inheritance can be defined as the process where one class acquires the properties (methods and fields) of another. With the use of inheritance the information is made manageable in a hierarchical order.

The class which inherits the properties of other is known as subclass (derived class, child class) and the class whose properties are inherited is known as superclass (base class, parent class).

The Superclass reference variable can hold the subclass object, but using that variable you can access only the members of the superclass, so to access the members of both classes it is recommended to always create reference variable to the subclass.

If you consider the above program, you can instantiate the class as given below. But using the superclass reference variable ( cal in this case) you cannot call the method multiplication(), which belongs to the subclass My_Calculation.

Calculation demo = new My_Calculation();
demo.addition(a, b);
demo.Subtraction(a, b);


Differentiating the Members
If a class is inheriting the properties of another class. And if the members of the superclass have the names same as the sub class, to differentiate these variables we use super keyword as shown below.

super.variable
super.method();
