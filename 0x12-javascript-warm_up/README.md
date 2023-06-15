0x12. JavaScript - Warm up
--------------------------------------------------------------------------------------------------
Learning Objectives: Why JavaScript programming is amazing How to run a JavaScript script How to create variables and constants What are differences between var, const and let What are all the data types available in JavaScript How to use the if, if ... else statements How to use comments How to affect values to variables How to use while and for loops How to use break and continue statements What is a function and how do you use functions What does a function that does not use any return statement return Scope of variables What are the arithmetic operators and how to use them How to manipulate dictionary How to import a file

General Requirements: Allowed editors: vi, vim, emacs, All  files will be interpreted on Ubuntu 20.04 LTS using node  All files should end with a new line, The first line of all files is exactly #!/usr/bin/node A README.md file, at the root of the folder of the project, Code is  semistandard compliant (version 16.x.x). Rules of Standard + semicolons on top. Also as reference: AirBnB style All files must be executable The files length was tested using wc
Tasks
------------------------------------------------------------------------------------------------------------
0. First constant, first print: A script that prints “JavaScript is amazing”: create a constant variable called myVar with the value “JavaScript is amazing”, use console.log(...) to print all output, not allowed to use var
Repo: GitHub repository: alx-higher_level_programming Directory: 0x12-javascript-warm_up File: 0-javascript_is_amazing.js
1. 3 languages: A script that prints 3 lines: The first line: “C is fun” The second line: “Python is cool” The third line: “JavaScript is amazing”, use console.log(...) to print all output, not allowed to use var
Repo: GitHub repository: alx-higher_level_programming Directory: 0x12-javascript-warm_up File: 1-multi_languages.js 
2. Arguments: A script that prints a message depending of the number of arguments passed: If no arguments are passed to the script, print “No argument” If only one argument is passed to the script, print “Argument found” Otherwise, print “Arguments found”, use console.log(...) to print all output, not allowed to use var Reference: process.argv
Repo: GitHub repository: alx-higher_level_programming Directory: 0x12-javascript-warm_up File: 2-arguments.js
3. Value of my argument: A script that prints the first argument passed to it: If no arguments are passed to the script, print “No argument”  use console.log(...) to print all output, not allowed to use var, not allowed to use length
Repo: GitHub repository: alx-higher_level_programming Directory: 0x12-javascript-warm_up File: 3-value_argument.js
4. Create a sentence: A script that prints two arguments passed to it, in the following format: “ is ” use console.log(...) to print all output, not allowed to use var
Repo: GitHub repository: alx-higher_level_programming Directory: 0x12-javascript-warm_up File: 4-concat.js
5. An Integer: A script that prints My number: <first argument converted in integer> if the first argument can be converted to an integer: If the argument can’t be converted to an integer, print “Not a number” use console.log(...) to print all output, not allowed to use var, not allowed to use try/catch
Repo: GitHub repository: alx-higher_level_programming Directory: 0x12-javascript-warm_up File: 5-to_integer.js
6. Loop to languages: A script that prints 3 lines: (like 1-multi_languages.js) but by using an array of string and a loop, The first line: “C is fun”, The second line: “Python is cool” The third line: “JavaScript is amazing” use console.log(...) to print all output, not allowed to use var, not allowed to use any if/else statement, use only one console.log, use a loop (while, for, etc.)
Repo: GitHub repository: alx-higher_level_programming Directory: 0x12-javascript-warm_up File: 6-multi_languages_loop.js
7. I love C: A script that prints x times “C is fun” Where x is the first argument of the script If the first argument can’t be converted to an integer, print “Missing number of occurrences use console.log(...) to print all output, not allowed to use var, use only two console.lo,  use a loop (while, for, etc.)
Repo: GitHub repository: alx-higher_level_programming Directory: 0x12-javascript-warm_up File: 7-multi_c.js
8. Square: A script that prints a square: The first argument is the size of the square, If the first argument can’t be converted to an integer, print “Missing size”, use the character X to print the square, use console.log(...) to print all output, not allowed to use var, use a loop (while, for, etc.)
Repo: GitHub repository: alx-higher_level_programming Directory: 0x12-javascript-warm_up File: 8-square.js   
9. Add: A script that prints the addition of 2 integers: The first argument is the first integer: The second argument is the second integer, Have to define a function with this prototype: function add(a, b), use console.log(...) to print all output, not allowed to use var
Repo: GitHub repository: alx-higher_level_programming, Directory: 0x12-javascript-warm_up, File: 9-add.js
10. Factorial: A script that computes and prints a factorial, The first argument is integer (argument can be cast as integer) used for computing the factorial, Factorial of NaN is 1, do it recursively, use a function, use console.log(...) to print all output, not allowed to use var
Repo: GitHub repository: alx-higher_level_programming Directory: 0x12-javascript-warm_up, File: 10-factorial.js
11. Second biggest! A script that searches the second biggest integer in the list of arguments. Assume all arguments can be converted to integer, If no argument passed, print 0, If the number of arguments is 1, print 0, use console.log(...) to print all output, not allowed to use var
Repo: GitHub repository: alx-higher_level_programming Directory: 0x12-javascript-warm_up File: 11-second_biggest.js
12. Object: Update this script to replace the value 12 with 89: not allowed to use va
Repo: GitHub repository: alx-higher_level_programming Directory: 0x12-javascript-warm_up File: 12-object.js 
13. Add fill: A function that returns the addition of 2 integers. The function must be visible from outside. The name of the function must be add, not allowed to use var
Repo: GitHub repository: alx-higher_level_programming Directory: 0x12-javascript-warm_up File: 13-add.js
14. Const or not const: A file that modifies the value of myVar to 333
Repo: GitHub repository: alx-higher_level_programming Directory: 0x12-javascript-warm_up File: 100-let_me_const.js
15. Call me Mob: A function that executes x times a function. The function must be visible from outside, Prototype: function (x, theFunction), not allowed to use var
Repo: GitHub repository: alx-higher_level_programming Directory: 0x12-javascript-warm_up File: 101-call_me_moby.js 
16. Add me maybe: A function that increments and calls a function. The function must be visible from outside, Prototype: function (number, theFunction), not allowed to use var
Repo: GitHub repository: alx-higher_level_programming Directory: 0x12-javascript-warm_up File: 102-add_me_maybe.js 
17. Increment object: Update this script by adding a new function incr that increments the integer value. Not allowed to use var
Repo: GitHub repository: alx-higher_level_programming Directory: 0x12-javascript-warm_up File: 103-object_fct.js
