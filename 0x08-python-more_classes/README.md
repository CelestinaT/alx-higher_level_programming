0x08. Python - More Classes and Objects
----------------------------------------------------------------------------------------------------------------
General Learning Objectives: Why Python programming is awesome? What is OOP? “first-class everything” What is a class? What is an object and an instance? What is the difference between a class and an object or instance? What is an attribute? What are and how to use public, protected and private attributes? What is self? What is a method? What is the special __init__ method and how to use it? What is Data Abstraction, Data Encapsulation, and Information Hiding? What is a property? What is the difference between an attribute and a property in Python? What is the Pythonic way to write getters and setters in Python? What are the special __str__ and __repr__ methods and how to use them? What is the difference between __str__ and __repr__? What is a class attribute? What is the difference between a object attribute and a class attribute? What is a class method? What is a static method? How to dynamically create arbitrary new attributes for existing instances of a class? How to bind attributes to object and classes? What is and what does contain __dict__ of a class and of an instance of a class? How does Python find the attributes of an object or class? How to use the getattr function?

Requirements
-------------------------------------------------------------------------------------------------------------------
Allowed editors: vi, vim, emacs. All your files will be interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.8.5). All your files should end with a new line. The first line of all your files should be exactly #!/usr/bin/python3. A README.md file, at the root of the folder of the project, is mandatory. Your code should use the pycodestyle (version 2.8.*). All your files must be executable. The length of your files will be tested using wc

Task 0. Simple rectangle
-----------------------------------------------------------------------------------------------------------------------------
Write an empty class Rectangle that defines a rectangle: You are not allowed to import any module
GitHub repository: alx-higher_level_programming
Directory: 0x08-python-more_classes
File: 0-rectangle.py


Task 1. Real definition of a rectangle
--------------------------------------------------------------------------------------------------------------------------------------
Write a class Rectangle that defines a rectangle by: (based on 0-rectangle.py)
Private instance attribute: width: property def width(self): to retrieve it. Property setter def width (self, value): to set it: width must be an integer, otherwise raise a TypeError exception with the message width must be an integer, if width is less than 0, raise a ValueError exception with the message width must be >= 0, Private instance attribute: height: property def height(self): to retrieve it, property setter def height(self, value): to set it: height must be an integer, otherwise raise a TypeError exception with the message height must be an integer if height is less than 0, raise a ValueError exception with the message height must be >= 0. Instantiation with optional width and height: def __init__(self, width=0, height=0): You are not allowed to import any module
GitHub repository: alx-higher_level_programming
Directory: 0x08-python-more_classes
File: 1-rectangle.py

Task 2. Area and Perimeter
------------------------------------------------------------------------------------------------------------
Write a class Rectangle that defines a rectangle by: (based on 1-rectangle.py)

Private instance attribute: width: property def width(self): to retrieve it, property setter def width (self, value): to set it: width must be an integer, otherwise raise a TypeError exception with the message width must be an integer if width is less than 0, raise a ValueError exception with the message width must be >= 0. Private instance attribute: height: property def height(self): to retrieve it, property setter def height(self, value): to set it: height must be an integer, otherwise raise a TypeError exception with the message height must be an integer if height is less than 0, raise a ValueError exception with the message height must be >= 0. Instantiation with optional width and height: def __init__(self, width=0, height=0): Public instance method: def area(self): that returns the rectangle area. Public instance method: def perimeter(self): that returns the rectangle perimeter: if width or height is equal to 0, perimeter is equal to 0. You are not allowed to import any module
GitHub repository: alx-higher_level_programming
Directory: 0x08-python-more_classes
File: 2-rectangle.py

Task 3. String representation
-------------------------------------------------------------------------------------------------------------------------------
Write a class Rectangle that defines a rectangle by: (based on 2-rectangle.py)
Private instance attribute: width: property def width(self): to retrieve it, property setter def width(self, value): to set it: width must be an integer, otherwise raise a TypeError exception with the message width must be an integer if width is less than 0, raise a ValueError exception with the message width must be >= 0. Private instance attribute: height: property def height(self): to retrieve it, property setter def height (self, value): to set it: height must be an integer, otherwise raise a TypeError exception with the message height must be an integer if height is less than 0, raise a ValueError exception with the message height must be >= 0. Instantiation with optional width and height: def __init__(self, width=0, height=0): Public instance method: def area(self): that returns the rectangle area. Public instance method: def perimeter(self): that returns the rectangle perimeter: if width or height is equal to 0, perimeter has to be equal to 0, print() and str() should print the rectangle with the character #: (see example below) if width or height is equal to 0, return an empty string. You are not allowed to import any module
GitHub repository: alx-higher_level_programming
Directory: 0x08-python-more_classes
File: 3-rectangle.py

Task 4. Eval is magic
----------------------------------------------------------------------------------------------------------------------------------
Write a class Rectangle that defines a rectangle by: (based on 3-rectangle.py)
Private instance attribute: width: property def width(self): to retrieve it, property setter def width(self, value): to set it: width must be an integer, otherwise raise a TypeError exception with the message width must be an integer if width is less than 0, raise a ValueError exception with the message width must be >= 0. Private instance attribute: height: property def height(self): to retrieve it, property setter def height(self, value): to set it: height must be an integer, otherwise raise a TypeError exception with the message height must be an integer if height is less than 0, raise a ValueError exception with the message height must be >= 0 Instantiation with optional width and height: def __init__(self, width=0, height=0): Public instance method: def area(self): that returns the rectangle area. Public instance method: def perimeter(self): that returns the rectangle perimeter: if width or height is equal to 0, perimeter has to be equal to 0 print() and str() should print the rectangle with the character #: (see example below) if width or height is equal to 0, return an empty string repr() should return a string representation of the rectangle to be able to recreate a new instance by using eval()  You are not allowed to import any module
GitHub repository: alx-higher_level_programming
Directory: 0x08-python-more_classes
File: 4-rectangle.py
 
Task 5. Detect instance deletion
-----------------------------------------------------------------------------------------------------------------------
Write a class Rectangle that defines a rectangle by: (based on 4-rectangle.py)
Private instance attribute: width: property def width(self): to retrieve it, property setter def width(self, value): to set it: width must be an integer, otherwise raise a TypeError exception with the message width must be an integer if width is less than 0, raise a ValueError exception with the message width must be >= 0. Private instance attribute: height: property def height(self): to retrieve it, property setter def height(self, value): to set it: height must be an integer, otherwise raise a TypeError exception with the message height must be an integer if height is less than 0, raise a ValueError exception with the message height must be >= 0. Instantiation with optional width and height: def __init__(self, width=0, height=0): Public instance method: def area(self): that returns the rectangle area. Public instance method: def perimeter(self): that returns the rectangle perimeter: if width or height is equal to 0, perimeter has to be equal to 0 print() and str() should print the rectangle with the character #: if width or height is equal to 0, return an empty string repr() should return a string representation of the rectangle to be able to recreate a new instance by using eval() Print the message Bye rectangle... (... being 3 dots not ellipsis) when an instance of Rectangle is deleted. You are not allowed to import any module
GitHub repository: alx-higher_level_programming
Directory: 0x08-python-more_classes
File: 5-rectangle.py
 
Task 6. How many instances
-----------------------------------------------------------------------------------------------------------------------
Write a class Rectangle that defines a rectangle by: (based on 5-rectangle.py)
Private instance attribute: width: property def width(self): to retrieve it property setter def width(self, value): to set it: width must be an integer, otherwise raise a TypeError exception with the message width must be an integer if width is less than 0, raise a ValueError exception with the message width must be >= 0. Private instance attribute: height: property def height(self): to retrieve it, property setter def height(self, value): to set it: height must be an integer, otherwise raise a TypeError exception with the message height must be an integer, if height is less than 0, raise a ValueError exception with the message height must be >= 0. Public class attribute number_of_instances: Initialized to 0, Incremented during each new instance instantiation, Decremented during each instance deletion, Instantiation with optional width and height: def __init__(self, width=0, height=0): Public instance method: def area(self): that returns the rectangle area, Public instance method: def perimeter(self): that returns the rectangle perimeter: if width or height is equal to 0, perimeter has to be equal to 0 print() and str() should print the rectangle with the character #: if width or height is equal to 0, return an empty string repr() should return a string representation of the rectangle to be able to recreate a new instance by using eval() Print the message Bye rectangle... (... being 3 dots not ellipsis) when an instance of Rectangle is deleted. You are not allowed to import any module
GitHub repository: alx-higher_level_programming
Directory: 0x08-python-more_classes
File: 6-rectangle.py

Task 8. Compare rectangles
---------------------------------------------------------------------------------------------------------
Write a class Rectangle that defines a rectangle by: (based on 7-rectangle.py)
Private instance attribute: width: property def width(self): to retrieve it, property setter def width(self, value): to set it: width must be an integer, otherwise raise a TypeError exception with the message width must be an integer if width is less than 0, raise a ValueError exception with the message width must be >= 0. Private instance attribute: height: property def height(self): to retrieve it, property setter def height(self, value): to set it: height must be an integer, otherwise raise a TypeError exception with the message height must be an integer, if height is less than 0, raise a ValueError exception with the message height must be >= 0 Public class attribute number_of_instances: Initialized to 0 Incremented during each new instance instantiation Decremented during each instance deletion Public class attribute print_symbol: Initialized to # Used as symbol for string representation can be any type, Instantiation with optional width and height: def __init__(self, width=0, height=0): Public instance method: def area(self): that returns the rectangle area Public instance method: def perimeter(self): that returns the rectangle perimeter: if width or height is equal to 0, perimeter has to be equal to 0 print() and str() should print the rectangle with the character #: if width or height is equal to 0, return an empty string repr() should return a string representation of the rectangle to be able to recreate a new instance by using eval() Print the message Bye rectangle... (... being 3 dots not ellipsis) when an instance of Rectangle is deleted Static method def bigger_or_equal(rect_1, rect_2): that returns the biggest rectangle based on the area rect_1 must be an instance of Rectangle, otherwise raise a TypeError exception with the message rect_1 must be an instance of Rectangle rect_2 must be an instance of Rectangle, otherwise raise a TypeError exception with the message rect_2 must be an instance of Rectangle. Returns rect_1 if both have the same area value. You are not allowed to import any module
GitHub repository: alx-higher_level_programming
Directory: 0x08-python-more_classes
File: 8-rectangle.py
 
Task 9. A square is a rectangle
--------------------------------------------------------------------------------------
Write a class Rectangle that defines a rectangle by: (based on 8-rectangle.py)
Private instance attribute: width: property def width(self): to retrieve it property setter def width(self, value): to set it: width must be an integer, otherwise raise a TypeError exception with the message width must be an integer if width is less than 0, raise a ValueError exception with the message width must be >= 0 Private instance attribute: height: property def height(self): to retrieve it property setter def height(self, value): to set it: height must be an integer, otherwise raise a TypeError exception with the message height must be an integer if height is less than 0, raise a ValueError exception with the message height must be >= 0 Public class attribute number_of_instances: Initialized to 0  Incremented during each new instance instantiation Decremented during each instance deletion Public class attribute print_symbol: Initialized to # Used as symbol for string representation Can be any type Instantiation with optional width and height: def __init__(self, width=0, height=0): Public instance method: def area(self): that returns the rectangle area Public instance method: def perimeter(self): that returns the rectangle perimeter: if width or height is equal to 0, perimeter has to be equal to 0 print() and str() should print the rectangle with the character #: if width or height is equal to 0, return an empty string repr() should return a string representation of the rectangle to be able to recreate a new instance by using eval() Print the message Bye rectangle... (... being 3 dots not ellipsis) when an instance of Rectangle is deleted. Static method def bigger_or_equal(rect_1, rect_2): that returns the biggest rectangle based on the area rect_1 must be an instance of Rectangle, otherwise raise a TypeError exception with the message rect_1 must be an instance of Rectangle rect_2 must be an instance of Rectangle, otherwise raise a TypeError exception with the message rect_2 must be an instance of Rectangle Returns rect_1 if both have the same area value Class method def square(cls, size=0): that returns a new Rectangle instance with width == height == size You are not allowed to import any module
GitHub repository: alx-higher_level_programming
Directory: 0x08-python-more_classes
File: 9-rectangle.py
Task 10. N queens
------------------------------------------------------------------------------------------------------------------------------
Chess grandmaster Judit Polgár, the strongest female chess player of all time

The N queens puzzle is the challenge of placing N non-attacking queens on an N×N chessboard. Write a program that solves the N queens problem. Usage: nqueens N If the user called the program with the wrong number of arguments, print Usage: nqueens N, followed by a new line, and exit with the status 1 where N must be an integer greater or equal to 4 If N is not an integer, print N must be a number, followed by a new line, and exit with the status 1 If N is smaller than 4, print N must be at least 4, followed by a new line, and exit with the status 1 The program should print every possible solution to the problem One solution per line You don’t have to print the solutions in a specific order You are only allowed to import the sys module Read: Queen, Backtracking
GitHub repository: alx-higher_level_programming
Directory: 0x08-python-more_classes
File: 101-nqueens.py
