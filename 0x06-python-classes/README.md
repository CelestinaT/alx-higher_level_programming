0x06. Python - Classes and Objects
--------------------------------------------------------------------------------------------------------
For this project, the major lessons are; Why Python programming is awesome? What is OOP? “first-class everything” What is a class? What is an object and an instance? What is the difference between a class and an object or instance? What is an attribute? What are and how to use public, protected and private attributes? What is self? What is a method? What is the special __init__ method and how to use it? What is Data Abstraction, Data Encapsulation, and Information Hiding? What is a property? What is the difference between an attribute and a property in Python? What is the Pythonic way to write getters and setters in Python. How to dynamically create arbitrary new attributes for existing instances of a class? How to bind attributes to object and classes? What is the __dict__ of a class and/or instance of a class and what does it contain? How does Python find the attributes of an object or class? How to use the getattr function

General Requirements
-----------------------------------------------------------------------------------------------------------
Allowed editors: vi, vim, emacs
All your files will be interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.8.5)
All your files should end with a new line
The first line of all your files should be exactly #!/usr/bin/python3
A README.md file, at the root of the folder of the project, is mandatory
Your code should use the pycodestyle (version 2.8.*)
All your files must be executable
The length of your files will be tested using wc
All your modules should have a documentation (python3 -c 'print(__import__("my_module").__doc__)')
All your classes should have a documentation (python3 -c 'print(__import__("my_module").MyClass.__doc__)')
All your functions (inside and outside a class) should have a documentation (python3 -c 'print(__import__("my_module").my_function.__doc__)' and python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)')
A documentation is not a simple word, it’s a real sentence explaining what’s the purpose of the module, class or method (the length of it will be verified)

Task 0. My first square
--------------------------------------------------------------------------------------
Write an empty class Square that defines a square: You are not allowed to import any module
GitHub repository: alx-higher_level_programming
Directory: 0x06-python-classes
File: 0-square.py
   
Task 1. Square with size
--------------------------------------------------------------------------------------------------------------------------
Write a class Square that defines a square by: (based on 0-square.py)

Private instance attribute: size, Instantiation with size (no type/value verification). You are not allowed to import any module. Why? Why size is private attribute? The size of a square is crucial for a square, many things depend of it (area computation, etc.), so you, as class builder, must control the type and value of this attribute. One way to have the control is to keep it privately. You will see in next tasks how to get, update and validate the size value.
GitHub repository: alx-higher_level_programming
Directory: 0x06-python-classes
File: 1-square.py
   
Task 2. Size validation
--------------------------------------------------------------------------------------------
Write a class Square that defines a square by: (based on 1-square.py)

Private instance attribute: size, Instantiation with optional size: def __init__(self, size=0):
size must be an integer, otherwise raise a TypeError exception with the message size must be an integer, if size is less than 0, raise a ValueError exception with the message size must be >= 0. You are not allowed to import any module
GitHub repository: alx-higher_level_programming
Directory: 0x06-python-classes
File: 2-square.py
   
Task 3. Area of a square
---------------------------------------------------------------------------------------------------
Write a class Square that defines a square by: (based on 2-square.py)

Private instance attribute: size. Instantiation with optional size: def __init__(self, size=0):
size must be an integer, otherwise raise a TypeError exception with the message size must be an integer, if size is less than 0, raise a ValueError exception with the message size must be >= 0. Public instance method: def area(self): that returns the current square area. You are not allowed to import any module
GitHub repository: alx-higher_level_programming
Directory: 0x06-python-classes
File: 3-square.py
   
Task 4. Access and update private attribute
--------------------------------------------------------------------------
Write a class Square that defines a square by: (based on 3-square.py)

Private instance attribute: size: property def size(self): to retrieve it, property setter def size(self, value): to set it: size must be an integer, otherwise raise a TypeError exception with the message size must be an integer, if size is less than 0, raise a ValueError exception with the message size must be >= 0. Instantiation with optional size: def __init__(self, size=0): Public instance method: def area(self): that returns the current square area. You are not allowed to import any module Why? Why a getter and setter? Reminder: size is a private attribute. We did that to make sure we control the type and value. Getter and setter methods are not 100% Python, but more OOP. With them, you will be able to validate the assignment of a private attribute and also define how getting the attribute value will be available from outside - by copy? by assignment? etc. Also, adding type/value validation in the setter will centralize the logic, since you will do it in only one place.
GitHub repository: alx-higher_level_programming
Directory: 0x06-python-classes
File: 4-square.py
   
Task 5. Printing a square
-----------------------------------------------------------------------------------------------------------------
Write a class Square that defines a square by: (based on 4-square.py)

Private instance attribute: size: property def size(self): to retrieve it
property setter def size(self, value): to set it: size must be an integer, otherwise raise a TypeError exception with the message size must be an integer if size is less than 0, raise a ValueError exception with the message size must be >= 0 Instantiation with optional size: def __init__(self, size=0): Public instance method: def area(self): that returns the current square area Public instance method: def my_print(self): that prints in stdout the square with the character #: if size is equal to 0, print an empty line. You are not allowed to import any module
GitHub repository: alx-higher_level_programming
Directory: 0x06-python-classes
File: 5-square.py
   
Task 6. Coordinates of a square
------------------------------------------------------------------------------------------------------------------------------
Write a class Square that defines a square by: (based on 5-square.py)

Private instance attribute: size: property def size(self): to retrieve it property setter def size(self, value): to set it: size must be an integer, otherwise raise a TypeError exception with the message size must be an integer if size is less than 0, raise a ValueError exception with the message size must be >= 0 Private instance attribute: position:
property def position(self): to retrieve it property setter def position(self, value): to set it:
position must be a tuple of 2 positive integers, otherwise raise a TypeError exception with the message position must be a tuple of 2 positive integers. Instantiation with optional size and optional position: def __init__(self, size=0, position=(0, 0)): Public instance method: def area(self): that returns the current square area. Public instance method: def my_print(self): that prints in stdout the square with the character #: if size is equal to 0, print an empty line
position should be use by using space - Don’t fill lines by spaces when position[1] > 0 You are not allowed to import any module
GitHub repository: alx-higher_level_programming
Directory: 0x06-python-classes
File: 6-square.py
   
Task 7. Singly linked list
--------------------------------------------------------------------------------------------------------------------------
Write a class Node that defines a node of a singly linked list by:

Private instance attribute: data: property def data(self): to retrieve it, property setter def data(self, value): to set it: data must be an integer, otherwise raise a TypeError exception with the message data must be an integer. Private instance attribute: next_node: property def next_node(self): to retrieve it, property setter def next_node(self, value): to set it:
next_node can be None or must be a Node, otherwise raise a TypeError exception with the message next_node must be a Node object. Instantiation with data and next_node: def __init__(self, data, next_node=None): And, write a class SinglyLinkedList that defines a singly linked list by: Private instance attribute: head (no setter or getter). Simple instantiation: def __init__(self): Should be printable: print the entire list in stdout
one node number by line. Public instance method: def sorted_insert(self, value): that inserts a new Node into the correct sorted position in the list (increasing order). You are not allowed to import any module
GitHub repository: alx-higher_level_programming
Directory: 0x06-python-classes
File: 100-singly_linked_list.py
   
Task 8. Print Square instance
-----------------------------------------------------------------------------------------------------
Write a class Square that defines a square by: (based on 6-square.py)

Private instance attribute: size: property def size(self): to retrieve it
property setter def size(self, value): to set it: size must be an integer, otherwise raise a TypeError exception with the message size must be an integer if size is less than 0, raise a ValueError exception with the message size must be >= 0. Private instance attribute: position: property def position(self): to retrieve it, property setter def position(self, value): to set it: position must be a tuple of 2 positive integers, otherwise raise a TypeError exception with the message position must be a tuple of 2 positive integer
Instantiation with optional size and optional position: def __init__(self, size=0, position=(0, 0)): Public instance method: def area(self): that returns the current square area. Public instance method: def my_print(self): that prints in stdout the square with the character #:
if size is equal to 0, print an empty line position should be use by using space. Printing a Square instance should have the same behavior as my_print(). You are not allowed to import any module
GitHub repository: alx-higher_level_programming
Directory: 0x06-python-classes
File: 101-square.py
   
Task 9. Compare 2 squares
----------------------------------------------------------------------------------------------------------------
Write a class Square that defines a square by: (based on 4-square.py)

Private instance attribute: size: property def size(self): to retrieve it, property setter def size(self, value): to set it: size must be a number (float or integer), otherwise raise a TypeError exception with the message size must be a number, if size is less than 0, raise a ValueError exception with the message size must be >= 0, Instantiation with size: def __init__(self, size=0): Public instance method: def area(self): that returns the current square area, Square instance can answer to comparators: ==, !=, >, >=, < and <= based on the square area. You are not allowed to import any module
GitHub repository: alx-higher_level_programming
Directory: 0x06-python-classes
File: 102-square.py
   
Task 10. ByteCode -> Python #5
--------------------------------------------------------------------------------------------------------
Write the Python class MagicClass that does exactly the same as the following Python bytecode:
GitHub repository: alx-higher_level_programming
Directory: 0x06-python-classes
File: 103-magic_class.py
   























0x05. Python - Exceptions
----------------------------------------------------------------------------------------------
The major lessons for this project are; Why Python programming is awesome? The difference between errors and exceptions, what are exceptions and how to use them. When do we need to use exception? How to correctly handle an exception. What’s the purpose of catching exceptions? How to raise a builtin exception? When do we need to implement a clean-up action after an exception

General Requirements
----------------------------------------------------------------------------------------------
Allowed editors: vi, vim, emacs
All your files will be interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.8.5)
All your files should end with a new line
The first line of all your files should be exactly #!/usr/bin/python3
A README.md file, at the root of the folder of the project, is mandatory
Your code should use the pycodestyle (version 2.8.*)
All your files must be executable
The length of your files will be tested using wc

Task 0. Safe list printing
----------------------------------------------------------------------
Write a function that prints x elements of a list.
Prototype: def safe_print_list(my_list=[], x=0): my_list can contain any type (integer, string, etc.) All elements must be printed on the same line followed by a new line. x represents the number of elements to print, x can be bigger than the length of my_list. Returns the real number of elements printed. You have to use try: / except, You are not allowed to import any module. You are not allowed to use len()
GitHub repository: alx-higher_level_programming
Directory: 0x05-python-exceptions
File: 0-safe_print_list.py 
 
Task 1. Safe printing of an integers list
---------------------------------------------------------------
Write a function that prints an integer with "{:d}".format().
Prototype: def safe_print_integer(value): value can be any type (integer, string, etc.) The integer should be printed followed by a new line. Returns True if value has been correctly printed (it means the value is an integer) Otherwise, returns False. You have to use try: / except: You have to use "{:d}".format() to print as integer. You are not allowed to import any module. You are not allowed to use type()
GitHub repository: alx-higher_level_programming
Directory: 0x05-python-exceptions
File: 1-safe_print_integer.py
   
Task 2. Print and count integers
--------------------------------------------------------------------------------------------------
Write a function that prints the first x elements of a list and only integers.

Prototype: def safe_print_list_integers(my_list=[], x=0): my_list can contain any type (integer, string, etc.) All integers have to be printed on the same line followed by a new line - other type of value in the list must be skipped (in silence). x represents the number of elements to access in my_list. x can be bigger than the length of my_list - if it’s the case, an exception is expected to occur. Returns the real number of integers printed. You have to use try: / except: You have to use "{:d}".format() to print an integer. You are not allowed to import any module. You are not allowed to use len()
GitHub repository: alx-higher_level_programming
Directory: 0x05-python-exceptions
File: 2-safe_print_list_integers.py
   
Task 3. Integers division with debug
---------------------------------------------------------------------------------------------------
Write a function that divides 2 integers and prints the result.

Prototype: def safe_print_division(a, b): You can assume that a and b are integers. The result of the division should print on the finally: section preceded by Inside result: Returns the value of the division, otherwise: None You have to use try: / except: / finally: You have to use "{}".format() to print the result. You are not allowed to import any module
GitHub repository: alx-higher_level_programming
Directory: 0x05-python-exceptions
File: 3-safe_print_division.py
   
Task 4. Divide a list
---------------------------------------------------------------------------------------------------------
Write a function that divides element by element 2 lists.

Prototype: def list_division(my_list_1, my_list_2, list_length): my_list_1 and my_list_2 can contain any type (integer, string, etc.) list_length can be bigger than the length of both lists. Returns a new list (length = list_length) with all divisions If 2 elements can’t be divided, the division result should be equal to 0 If an element is not an integer or float: print: wrong type. If the division can’t be done (/0): print: division by 0. If my_list_1 or my_list_2 is too short, print: out of range. You have to use try: / except: / finally: You are not allowed to import any module
GitHub repository: alx-higher_level_programming
Directory: 0x05-python-exceptions
File: 4-list_division.py
   
Task 5. Raise exception
----------------------------------------------------------------------------------------------------
Write a function that raises a type exception.

Prototype: def raise_exception(): You are not allowed to import any module
GitHub repository: alx-higher_level_programming
Directory: 0x05-python-exceptions
File: 5-raise_exception.py
   
Task 6. Raise a message
----------------------------------------------------------------------------------------------
Write a function that raises a name exception with a message.

Prototype: def raise_exception_msg(message=""): You are not allowed to import any module
GitHub repository: alx-higher_level_programming
Directory: 0x05-python-exceptions
File: 6-raise_exception_msg.py
   
Task 7. Safe integer print with error message
---------------------------------------------------------------------------------------------------
Write a function that prints an integer.

Prototype: def safe_print_integer_err(value): value can be any type (integer, string, etc.) The integer should be printed followed by a new line. Returns True if value has been correctly printed (it means the value is an integer). Otherwise, returns False and prints in stderr the error precede by Exception: You have to use try: / except: You have to use "{:d}".format() to print as integer. You are not allowed to use type()
GitHub repository: alx-higher_level_programming
Directory: 0x05-python-exceptions
File: 100-safe_print_integer_err.py
   
Task 8. Safe function
--------------------------------------------------------------------------------------------------------------------
Write a function that executes a function safely.

Prototype: def safe_function(fct, *args):You can assume fct will be always a pointer to a function. Returns the result of the function, Otherwise, returns None if something happens during the function and prints in stderr the error precede by Exception: You have to use try: / except:
GitHub repository: alx-higher_level_programming
Directory: 0x05-python-exceptions
File: 101-safe_function.py
   
Task 9. ByteCode -> Python #4
------------------------------------------------------------------------------------
Write the Python function def magic_calculation (a, b)

GitHub repository: alx-higher_level_programming
Directory: 0x05-python-exceptions
File: 102-magic_calculation.py
   
Task 10. CPython #2: PyFloatObject
-------------------------------------------------------------------------------------------------------
Create three C functions that print some basic info about Python lists, Python bytes an Python float objects.
GitHub repository: alx-higher_level_programming
Directory: 0x05-python-exceptions
File: 103-python.c
