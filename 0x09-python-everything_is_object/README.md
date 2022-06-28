# 0x09. Python - Everything is object

## Background Context
Now that we understand that everything is an object and have a little bit of knowledge, let’s pause and look a little bit closer at how Python works with different types of objects.

BTW, have you ever modified a variable without knowing it or wanting to? I mean:

        >>> a = 1
        >>> b = a
        >>> a = 2
        >>> b
        1
        >>> 

OK. But what about this?

        >>> l = [1, 2, 3]
        >>> m = l
        >>> l[0] = 'x'
        >>> m
        ['x', 2, 3]
        >>> 



This project is a little bit different than the usual projects. The first part is only questions about Python’s specificity like “What would be the result of…”. You should read all documentation first (as usual :)), then take the time to think and brainstorm with your peers about what you think and why. Try to do this without coding anything for a few hours.

Trying examples in the Python interpreter will give you most of the answers without having to think about it. Don’t go this route. First read, then think, then brainstorm together. Only then you can test in the interpreter.

It’s important that you truly understand the reasons behind the answers of all those tasks so that you can apply the same logic to other variables and other variable types. The biggest mandatory task is the blog post and it will count for 50% of the total score of the project.

Note that during interviews for Python positions, you will most likely have to answer to these type of questions.

All your answers should be only one line in a file. No space before or after the answer.

## Resources
## Read or watch:

9.10. Objects and values
9.11. Aliasing
Immutable vs mutable types
Mutation (Only this chapter)
9.12. Cloning lists
Python tuples: immutable but potentially changing

## Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

## General
* Why Python programming is awesome
* What is an object
* What is the difference between a class and an object or instance
* What is the difference between immutable object and mutable object
* What is a reference
* What is an assignment
* What is an alias
* How to know if two variables are identical
* How to know if two variables are linked to the same object
* How to display the variable identifier (which is the memory address in the CPython implementation)
* What is mutable and immutable
* What are the built-in mutable types
* What are the built-in immutable types
* How does Python pass variables to functions


## Copyright - Plagiarism
* You are tasked to come up with solutions for the tasks below yourself to meet with the above learning objectives.
* You will not be able to meet the objectives of this or any following project by copying and pasting someone else’s work.
* You are not allowed to publish any content of this project.
* Any form of plagiarism is strictly forbidden and will result in removal from the program.

## Requirements
## Python Scripts

Allowed editors: vi, vim, emacs
All your files will be interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.8.5)
All your files should end with a new line
The first line of all your files should be exactly #!/usr/bin/python3
A README.md file, at the root of the folder of the project, is mandatory
Your code should use the pycodestyle (version 2.8.*)
All your files must be executable
The length of your files will be tested using wc

## .txt Answer Files
Only one line
No Shebang
All your files should end with a new line

## More Info
Manual QA Review
It is your responsibility to request a review for your blog from a peer before the project’s deadline. If no peers have been reviewed, you should request a review from a TA or staff member.
---

--- TASKS

### [0. Who am I?](./0-answer.txt)
* What function would you use to print the type of an object?


### [1. Where are you?](./1-answer.txt)
* How do you get the variable identifier (which is the memory address in the CPython implementation)?


### [2. Right count](./2-answer.txt)
* In the following code, do a and b point to the same object?
Answer with Yes or No.


### [3. Right count =](./3-answer.txt)
* In the following code, do a and b point to the same object?
Answer with Yes or No.


### [4. Right count =](./4-answer.txt)
* In the following code, do a and b point to the same object?
Answer with Yes or No.


### [5. Right count =+](./5-answer.txt)
* In the following code, do a and b point to the same object?
Answer with Yes or No.


### [6. Is equal](./6-answer.txt)
* What do these 3 lines print?


### [7. Is the same](./7-answer.txt)
* What do these 3 lines print?


### [8. Is really equal](./8-answer.txt)
* What do these 3 lines print?


### [9. Is really the same](./9-answer.txt)
* What do these 3 lines print?


### [10. And with a list, is it equal](./10-answer.txt)
* What do these 3 lines print?


### [11. And with a list, is it the same](./11-answer.txt)
* What do these 3 lines print?


### [12. And with a list, is it really equal](./12-answer.txt)
* What do these 3 lines print?


### [13. And with a list, is it really the same](./13-answer.txt)
* What do these 3 lines print?


### [14. List append](./14-answer.txt)
* What does this script print?


### [15. List add](./15-answer.txt)
* What does this script print?


### [16. Integer incrementation](./16-answer.txt)
* What does this script print?


### [17. List incrementation](./17-answer.txt)
* What does this script print?


### [18. List assignation](./18-answer.txt)
* What does this script print?


### [19. Copy a list object](./19-copy_list.py)
* Write a function def copy_list(l): that returns a copy of a list.


### [20. Tuple or not?](./20-answer.txt)
* a = ()



### [21. Tuple or not?](./21-answer.txt)
* a = (1, 2)



### [22. Tuple or not?](./22-answer.txt)
* a = (1)



### [23. Tuple or not?](./23-answer.txt)
* a = (1, )



### [24. Who I am?](./24-answer.txt)
* What does this script print?


### [25. Tuple or not](./25-answer.txt)
* What does this script print?


### [26. Empty is not empty](./26-answer.txt)
* What does this script print?


### [27. Still the same?](./27-answer.txt)
* >>> id(a)
139926795932424
>>> a
[1, 2, 3, 4]
>>> a = a + [5]
>>> id(a)



### [28. Same or not?](./28-answer.txt)
* >>> a
[1, 2, 3]
>>> id (a)
139926795932424
>>> a += [4]
>>> id(a)



### [29. #pythonic](./106-line1.txt)
* Write a function magic_string() that returns a string “BestSchool” n times the number of the iteration 



### [30. Low memory cost](./101-locked_class.py)
Write a class LockedClass with no class or object attribute, that prevents the user from dynamically creating new instance attributes, except if the new instance attribute is called first_name.

You are not allowed to import any module



### [31. int 1/3](./103-line1.txt, 103-line2.txt)
* Assuming we are using a CPython implementation of Python3 with default options/configuration:

How many int objects are created by the execution of the first line of the script? (103-line1.txt)
How many int objects are created by the execution of the second line of the script (103-line2.txt) 



### [32. int 2/3](./104-line1.txt, 104-line2.txt, 104-line3.txt, 104-line4.txt, 104-line5.txt)
* Assuming we are using a CPython implementation of Python3 with default options/configuration:

How many int objects are created by the execution of the first line of the script? (104-line1.txt)
How many int objects are created by the execution of the second line of the script (104-line2.txt)
After the execution of line 3, is the int object pointed by a deleted? Answer with Yes or No (104-line3.txt)
After the execution of line 4, is the int object pointed by b deleted? Answer with Yes or No (104-line4.txt)
How many int objects are created by the execution of the last line of the script (104-line5.txt)



### [33. int 3/3](./105-line1.txt)
* Assuming we are using a CPython implementation of Python3 with default options/configuration:

Before the execution of line 2 (print("Love")), how many int objects have been created and are still in memory? (105-line1.txt)
Why? (optional blog post :))
Hint: NSMALLPOSINTS, NSMALLNEGINTS



### [34. Clear strings](./106-line1.txt, 106-line2.txt, 106-line3.txt, 106-line4.txt, 106-line5.txt)
* Assuming we are using a CPython implementation of Python3 with default options/configuration (For answers with numbers use integers, don’t spell out the word):

How many string objects are created by the execution of the first line of the script? (106-line1.txt)
How many string objects are created by the execution of the second line of the script (106-line2.txt)
After the execution of line 3, is the string object pointed by a deleted? Answer with Yes or No (106-line3.txt)
After the execution of line 4, is the string object pointed by b deleted? Answer with Yes or No (106-line4.txt)
How many string objects are created by the execution of the last line of the script (106-line5.txt)

---
