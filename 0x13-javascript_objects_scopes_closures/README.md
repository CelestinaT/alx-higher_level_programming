0x13. JavaScript - Objects, Scopes and Closures
------------------------------------------------------------------------------------
Learning Objectives: Why JavaScript programming is amazing, How to create an object in JavaScript, What this means, What undefined means, Why the variable type and scope is important, What is a closure, What is a prototype, How to inherit an object from another
General Requirements: Allowed editors: vi, vim, emacs, All files will be interpreted on Ubuntu 20.04 LTS using node, All files should end with a new line, The first line of all your files should be exactly #!/usr/bin/node, A README.md file, at the root of the folder of the project, is mandatory, Code should be semistandard compliant. Rules of Standard + semicolons on top. Also as reference: AirBnB style, All files must be executable, The length of files will be tested using wc, You are not allowed to use var

Tasks
----------------------------------------------------------------------------------------------------------
0. Rectangle #0: An empty class Rectangle that defines a rectangle: use the class notation for defining your class. 
Repo: GitHub repository: alx-higher_level_programming Directory: 0x13-javascript_objects_scopes_closures File: 0-rectangle.js
1. Rectangle #1 a class Rectangle that defines a rectangle: use the class notation for defining your class. The constructor must take 2 arguments w and h, Initialize the instance attribute width with the value of w, Initialize the instance attribute height with the value of h 
Repo: GitHub repository: alx-higher_level_programming Directory: 0x13 javascript_objects_scopes_closures File: 1-rectangle.js
2. Rectangle #2: A class Rectangle that defines a rectangle: use the class notation for defining your class. The constructor must take 2 arguments w and h, Initialize the instance attribute width with the value of w, Initialize the instance attribute height with the value of h, If w or h is equal to 0 or not a positive integer, create an empty object
Repo: GitHub repository: alx-higher_level_programming Directory: 0x13-javascript_objects_scopes_closures File: 2-rectangle.js
3. Rectangle #3: A class Rectangle that defines a rectangle: use the class notation for defining your class The constructor must take 2 arguments: w and h Initialize the instance attribute width with the value of w Initialize the instance attribute height with the value of h, If w or h is equal to 0 or not a positive integer, create an empty object, Create an instance method called print() that prints the rectangle using the character X
Repo: GitHub repository: alx-higher_level_programming Directory: 0x13-javascript_objects_scopes_closures File: 3-rectangle.js 
4. Rectangle #4: A class Rectangle that defines a rectangle: use the class notation for defining your class, The constructor must take 2 arguments: w and h, Initialize the instance attribute width with the value of w, Initialize the instance attribute height with the value of h, If w or h is equal to 0 or not a positive integer, create an empty object, Create an instance method called print() that prints the rectangle using the character X, Create an instance method called rotate() that exchanges the width and the height of the rectangle Create an instance method called double() that multiples the width and the height of the rectangle by 2
Repo: GitHub repository: alx-higher_level_programming Directory: 0x13-javascript_objects_scopes_closuresFile: 4-rectangle.js 
5. Square #0: A class Square that defines a square and inherits from Rectangle of 4-rectangle.js: use the class notation for defining your class and extends. The constructor must take 1 argument: size. The constructor of Rectangle must be called (by using super())
Repo: GitHub repository: alx-higher_level_programming Directory: 0x13-javascript_objects_scopes_closures File: 5-square.js  
6. Square #1: A class Square that defines a square and inherits from Square of 5-square.js: use the class notation for defining your class and extends. Create an instance method called charPrint(c) that prints the rectangle using the character c If c is undefined, use the character X
Repo: GitHub repository: alx-higher_level_programming Directory: 0x13-javascript_objects_scopes_closures File: 6-square.js
7. Occurrences: A function that returns the number of occurrences in a list: Prototype: exports.nbOccurences = function (list, searchElement)
Repo: GitHub repository: alx-higher_level_programming Directory: 0x13-javascript_objects_scopes_closures File: 7-occurrences.js
8. Esrever: A function that returns the reversed version of a list: Prototype: exports.esrever = function (list), Not allow to use the built-in method reverse
Repo: GitHub repository: alx-higher_level_programming Directory: 0x13-javascript_objects_scopes_closures
File: 8-esrever.js  
9. Log me: A function that prints the number of arguments already printed and the new argument value. (see example below), Prototype: exports.logMe = function (item) Output format: <number arguments already printed>: <current argument value>
Repo: GitHub repository: alx-higher_level_programming Directory: 0x13-javascript_objects_scopes_closures File: 9-logme.js
10. Number conversion: A function that converts a number from base 10 to another base passed as argument: Prototype: exports.converter = function (base) Not allowed to import any file, Not allowed to declare any new variable (var, let, etc..)
Repo: GitHub repository: alx-higher_level_programming Directory: 0x13-javascript_objects_scopes_closures File: 10-converter.js
11. Factor index: A script that imports an array and computes a new array. Script must import list from the file 100-data.js. Use a map. A new list must be created with each value equal to the value of the initial list, multipled by the index in the list. Print both the initial list and the new list
Repo: GitHub repository: alx-higher_level_programming Directory: 0x13-javascript_objects_scopes_closures File: 100-map.js 
12. Sorted occurences: A script that imports a dictionary of occurrences by user id and computes a dictionary of user ids by occurrence. Script must import dict from the file 101-data.js. In the new dictionary: A key is a number of occurrences, A value is the list of user ids, Print the new dictionary at the end
Repo: GitHub repository: alx-higher_level_programming Directory: 0x13-javascript_objects_scopes_closures File: 101-sorted.js 
13. Concat files: A script that concats 2 files, The first argument is the file path of the first source file, The second argument is the file path of the second source file, The third argument is the file path of the destination
Repo: GitHub repository: alx-higher_level_programming Directory: 0x13-javascript_objects_scopes_closures File: 102-concat.js
