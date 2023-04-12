0x0A. Python – Inheritance
-------------------------------------------------------------------------------------------------------------------
Learning Objectives: Why Python programming is awesome? What is a superclass, baseclass or parentclass? What is a subclass? How to list all attributes and methods of a class or instance? When can an instance have new attributes? How to inherit class from another? How to define a class with multiple base classes? What is the default class every class inherit from? How to override a method or attribute inherited from the base class? Which attributes or methods are available by heritage to subclasses? What is the purpose of inheritance? What are, when and how to use isinstance, issubclass, type and super built-in functions
Requirements
--------------------------------------------------------------------------------------------------------------------------
Python Scripts: Allowed editors: vi, vim, emacs, All files will be interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.8.5), All your files should end with a new line, The first line of all your files should be exactly #!/usr/bin/python3, A README.md file, at the root of the folder of the project, is mandatory, Code should use the pycodestyle (version 2.8.*), All your files must be executable, The length of files will be tested using wc

Python Test Cases: Allowed editors: vi, vim, emacs, All your files should end with a new line, All test files should be inside a folder tests, All  test files should be text files (extension: .txt), All  tests should be executed by using this command: python3 -m doctest ./tests/*, All modules should have a documentation (python3 -c 'print(__import__("my_module").__doc__)'), All classes should have a documentation (python3 -c 'print(__import__("my_module").MyClass.__doc__)'), All  functions (inside and outside a class) should have a documentation (python3 -c 'print(__import__("my_module").my_function.__doc__)' and python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)')
Task 0. Lookup
--------------------------------------------------------------------------------------------------------------------------
Write a function that returns the list of available attributes and methods of an object:
Prototype: def lookup(obj): Returns a list object. You are not allowed to import any module Repo: GitHub repository: alx-higher_level_programming Directory: 0x0A-python-inheritance File: 0-lookup.py
 
Task 1. My list
--------------------------------------------------------------------------------------------------------------------------------------
Write a class MyList that inherits from list:
Public instance method: def print_sorted(self): that prints the list, but sorted (ascending sort). You can assume that all the elements of the list will be of type int. You are not allowed to import any module Repo: GitHub repository: alx-higher_level_programming Directory: 0x0A-python-inheritance File: 1-my_list.py, tests/1-my_list.txt
Task 2. Exact same object
---------------------------------------------------------------------------------------------------------------------------
Write a function that returns True if the object is exactly an instance of the specified class; otherwise False.
Prototype: def is_same_class(obj, a_class): You are not allowed to import any module Repo: GitHub repository: alx-higher_level_programming Directory: 0x0A-python-inheritance File: 2-is_same_class.py

Task 3. Same class or inherit from
--------------------------------------------------------------------------------------------------------------------------
Write a function that returns True if the object is an instance of, or if the object is an instance of a class that inherited from, the specified class ; otherwise False.
Prototype: def is_kind_of_class(obj, a_class): You are not allowed to import any module Repo: GitHub repository: alx-higher_level_programming Directory: 0x0A-python-inheritance File: 3-is_kind_of_class.py
 
Task 4. Only sub class of
------------------------------------------------------------------------------------------------------
Write a function that returns True if the object is an instance of a class that inherited (directly or indirectly) from the specified class ; otherwise False.
Prototype: def inherits_from(obj, a_class): You are not allowed to import any module Repo: GitHub repository: alx-higher_level_programming Directory: 0x0A-python-inheritance File: 4-inherits_from.py
 
Task 5. Geometry module
------------------------------------------------------------------------------------------------------
Write an empty class BaseGeometry. You are not allowed to import any module Repo:
GitHub repository: alx-higher_level_programming Directory: 0x0A-python-inheritance File: 5-base_geometry.py
Task 6. Improve Geometry
--------------------------------------------------------------------------------------------------------
Write a class BaseGeometry (based on 5-base_geometry.py).
Public instance method: def area(self): that raises an Exception with the message area() is not implemented You are not allowed to import any module Repo: GitHub repository: alx-higher_level_programming Directory: 0x0A-python-inheritance File: 6-base_geometry.py
 
Task 7. Integer validator
---------------------------------------------------------------------------------------------------------------
Write a class BaseGeometry (based on 6-base_geometry.py).
Public instance method: def area(self): that raises an Exception with the message area() is not implemented. Public instance method: def integer_validator(self, name, value): that validates value: you can assume name is always a string if value is not an integer: raise a TypeError exception, with the message <name> must be an integer if value is less or equal to 0: raise a ValueError exception with the message <name> must be greater than 0. You are not allowed to import any module
Repo: GitHub repository: alx-higher_level_programming Directory: 0x0A-python-inheritance File: 7-base_geometry.py, tests/7-base_geometry.txt
 
Task 8. Rectangle
------------------------------------------------------------------------------------------------------------------------------
Write a class Rectangle that inherits from BaseGeometry (7-base_geometry.py). Instantiation with width and height: def __init__(self, width, height): width and height must be private. No getter or setter width and height must be positive integers, validated by integer_validator Repo: GitHub repository: alx-higher_level_programming Directory: 0x0A-python-inheritance File: 8-rectangle.py
Task 9. Full rectangle
---------------------------------------------------------------------------------------------------------------------
Write a class Rectangle that inherits from BaseGeometry (7-base_geometry.py). (task based on 8-rectangle.py) Instantiation with width and height: def __init__(self, width, height):: width and height must be private. No getter or setter width and height must be positive integers validated by integer_validator the area() method must be implemented print() should print, and str() should return, the following rectangle description: [Rectangle] <width>/<height>
Repo: GitHub repository: alx-higher_level_programming Directory: 0x0A-python-inheritance File: 9-rectangle.py
 
Task 10. Square #1
------------------------------------------------------------------------------------------------------------------------
Write a class Square that inherits from Rectangle (9-rectangle.py):
Instantiation with size: def __init__(self, size):: size must be private. No getter or setter size must be a positive integer, validated by integer_validator the area() method must be implemented 
Repo: GitHub repository: alx-higher_level_programming Directory: 0x0A-python-inheritance File: 10-square.py

Task 11. Square #2
------------------------------------------------------------------------------------------------------------------------------
Write a class Square that inherits from Rectangle (9-rectangle.py). (task based on 10-square.py).
Instantiation with size: def __init__(self, size):: size must be private. No getter or setter size must be a positive integer, validated by integer_validator the area() method must be implemented print() should print, and str() should return, the square description: [Square] <width>/<height>
Repo: GitHub repository: alx-higher_level_programming Directory: 0x0A-python-inheritance File: 11-square.py

Task 12. My integer
-------------------------------------------------------------------------------------------------------------------------------
Write a class MyInt that inherits from int:
MyInt is a rebel. MyInt has == and != operators inverted. You are not allowed to import any module
Repo: GitHub repository: alx-higher_level_programming Directory: 0x0A-python-inheritance File: 100-my_int.py
 
Task 13. Can I?
-----------------------------------------------------------------------------------------------------------------------------
Write a function that adds a new attribute to an object if it’s possible:
Raise a TypeError exception, with the message can't add new attribute if the object can’t have new attribute. Not allowed to use try/except. Not allowed to import any module. Repo: GitHub repository: alx-higher_level_programming Directory: 0x0A-python-inheritance File: 101-add_attribute.py

