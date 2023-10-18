# Constructor-overloading

THEORY 

In C++, We can have more than one constructor in a class with same name, as long as each has a different list of arguments.This concept is known as Constructor Overloading and is quite similar to function overloading. 
 

Overloaded constructors essentially have the same name (exact name of the class) and different by number and type of arguments.
A constructor is called depending upon the number and type of arguments passed.
While creating the object, arguments must be passed to let compiler know, which constructor needs to be called. 

ALGORITHM

art-A

Constructor Overloading Algorithm:

1.Start

2.Define a class with multiple constructor declarations, each with a different parameter list. These constructors may have different numbers or types of parameters.

3.Inside each constructor, initialize the object's member variables using the provided arguments.

4.Optionally, perform any necessary initialization or validation logic inside the constructors.

5.Create objects of the class by specifying different sets of arguments when invoking the constructors.

6.When creating an object, the compiler will determine which constructor to call based on the number and types of arguments provided.

7.Use the objects to access member variables and member functions as needed.

8.End

Part-B
1.Include the necessary header file for input and output (iostream).

2.Declare a class named area.

3.Inside the area class, declare two private member variables length and width, both of type float.

4.Define a default constructor for the area class:

5.Initialize the length member variable to 10.

6.Initialize the width member variable to 20.

7.Calculate the area (ar) as the product of length and width.

8.Display a message indicating the area of the room using cout.

9.Define a parameterized constructor for the area class that takes two float arguments (l and b):

10.Initialize the length member variable with the value of l.

11.Initialize the width member variable with the value of b.

12.Calculate the area (ar) as the product of length and width.

13.Display a message indicating the area of the room using cout.

14.In the main function:

15.Create three objects of the area class (A1, A2, and A3) using different constructors.

16.For A1, the default constructor is used, which sets length to 10 and width to 20, and calculates the area based on these values.

17.For A2, a parameterized constructor is used with the arguments 11.52 and 20. It sets length to 11.52 and width to 20 and calculates the area accordingly.

18.For A3, a parameterized constructor is used with the arguments 15.20 and 20.20. It sets length to 15.20 and width to 20.20 and calculates the area based on these values.

19.Return 0 to indicate successful program termination.

20.This code defines a class for calculating and displaying the area of a room, providing both default and parameterized constructors for flexibility in specifying the room's dimensions.

Part-C
1.Include the necessary header file for input and output (iostream).

2.Declare a class named construct.

3.Inside the construct class, declare two integer member variables a and b.

4.Define a default constructor for the construct class:

5.Initialize a to 10.

6.Print the value of a using cout.

7.Define a constructor that takes one integer argument x for the construct class:

8.Set the member variable a to 29.

9.Print the value of x using cout.

10.Define a constructor that takes two integer arguments a_val and b_val for the construct class:

11.Set the member variables a and b to the values of a_val and b_val, respectively.

12.Print the values of a and b using cout.

13.Define a constructor that takes one integer argument a_val and one float argument b_val for the construct class:

14.Set the member variable a to the value of a_val.

15.Print the value of a using cout.

16.Print the value of b_val using cout.

17.In the main function:

18.Create four objects of the construct class (obj1, obj2, obj3, and obj4) using different constructors.

19.Display the values of a and b for each object using the cout statements within the constructors.

20.Return 0 to indicate successful program termination.

OUTPUT

Part A

A=10

A=20

A=10

Part B

the area of room is: 200

the area of room is: 230.4

the area of room is: 307.04

Part C

a: 10

x: 42

a: 20

b: 30

a: 123

b: 12.22

