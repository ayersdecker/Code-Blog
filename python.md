---
title: Python
layout: default
---

Hello World!

Hello Future Programmers! Congratulations on making the first step into learning how to code. The language we will use is Python. Python is a programming language that is easy to learn and it is used widely across the industry. 

So for our first tutorial we will open up the VSC, which you have installed on your computer. 

Create a new file called “HelloWorld.py”.

Open up the file and write print(“Hello World)” which should print out “Hello World”. 

There you go we have created and ran your first program! Hopefully this leads to an exciting journey into learning python.



Exercise: 
Print out your name and birth date using a single print().
Hint: use “\n”



Variables and Types

Welcome back! After learning how to print “Hello World” onto the command line. I bet you are dying to learn some python! So, I will do what you ask.

In this tutorial, we will learn about types. You see, Python has a bunch of different built-in data types. 

These types range from 
Text Type:
str(string)
Numeric Types
Int
Float
Complex
	Sequence: 
List
Tuple
Complex
	Mapping Type:
dict(dictionary)
	Set Types: 
Set
Frozenset
	Boolean Type:
bool(boolean)
	Binary Types
Bytes
Byte array,
Memory View
	None Type
NoneType

Open your Visual Studio Code and create a file called “variables.py”. 
Open it and write “print(type(“Hello World”)). It should return “str”.

Exercise: 
Have fun and test out any value that you want within the print(type(random value));




Lists

Welcome once more, eager programmers!

Having gotten comfortable with "Hello, World!" and various data types, we're now ready to tackle Lists in Python. Think of Lists as a collection of items, like a treasure chest, except instead of gold and jewels, it holds data (which is just as valuable in the world of programming!).

In this tutorial, we'll discover how to create, access, modify, and utilize Lists to enhance our Python skills.

Creating a List:
- To start, we make a list with square brackets [ ] and separate each item with a comma.
  Example:
    my_sports_list = ['soccer', 'basketball', 'baseball']
    print(my_sports_list)

Accessing List Elements:
- Lists are like a team lineup, and each player has a position. We start counting from 0.
  Example:
    print(my_sports_list[1])  # This will print 'basketball' because it's the second item, but at index 1.

Modifying Lists:
- Lists are flexible; we can update them as needed.
  Example:
    my_sports_list[2] = 'volleyball'  # This changes 'baseball' to 'volleyball'.
    print(my_sports_list)  # Now the list is ['soccer', 'basketball', 'volleyball'].

Adding to Lists:
- Just like adding a player to a team, you can append items to a list.
  Example:
    my_sports_list.append('tennis')  # This adds 'tennis' to the end of the list.
    print(my_sports_list)  # The list is now ['soccer', 'basketball', 'volleyball', 'tennis'].

Removing from Lists:
- If a player leaves the team, you can also remove them from the list.
  Example:
    my_sports_list.remove('soccer')  # This will take 'soccer' out of the list.
    print(my_sports_list)  # The list is now ['basketball', 'volleyball', 'tennis'].

List Length:
- To see how many sports are in your list, you can use the len() function.
  Example:
    print(len(my_sports_list))  # This will print '3' because there are three items in the list.

List Slicing:
- You can select a team of the week by slicing the list, which means taking just a part of it.
  Example:
    print(my_sports_list[1:3])  # This will print ['basketball', 'volleyball'], which is a slice of my_sports_list starting from index 1 up to but not including index 3.

Combining Lists:
- You can merge two sports teams into a bigger list.
  Example:
    another_sports_list = ['golf', 'swimming']
    combined_sports_list = my_sports_list + another_sports_list
    print(combined_sports_list)  # The list is now ['basketball', 'volleyball', 'tennis', 'golf', 'swimming'].

Iterating through Lists:
- You can go through the list and announce each sport.
  Example:
    for sport in my_sports_list:
        print("I like to play", sport)
    # This will print each item in my_sports_list on a new line, preceded by 'I like to play'.

Exercise:
- Create a list of your favorite sports.
- Add two more sports to the list.
- Remove one sport from the list.
- Print out each sport in the list using a for loop.

End of Lists Section



Basic Operators

Hello, bright minds!

We've conquered variables, types, and lists, and now it's time to arm ourselves with the tools of calculation and comparison – the basic operators. These are the symbols that allow us to perform arithmetic, make comparisons, and manipulate data.

Arithmetic Operators:
- Just like in math, we can add (+), subtract (-), multiply (*), and divide (/) numbers in Python.
  Example:
    addition = 5 + 3
    subtraction = 5 - 3
    multiplication = 5 * 3
    division = 5 / 3
    print(addition, subtraction, multiplication, division)

Comparison Operators:
- When you need to compare values, Python has got you covered with comparison operators.
  Example:
    print(5 > 3)  # Is 5 greater than 3? This prints True.
    print(5 < 3)  # Is 5 less than 3? This prints False.
    print(5 == 5) # Is 5 equal to 5? This prints True.

Logical Operators:
- Combine boolean values (True or False) using and, or, not.
  Example:
    print((5 > 3) and (5 > 4)) # Both conditions are true, so this prints True.
    print((5 > 3) or (3 > 5))  # One condition is true, so this prints True.
    print(not(5 > 3))          # The opposite of True is False, so this prints False.

Assignment Operators:
- These operators are used to assign values to variables.
  Example:
    x = 10       # Assign 10 to x.
    x += 5       # Add 5 to x, now x is 15.
    print(x)

Exercise:
- Use each arithmetic operator with numbers of your choice.
- Compare two values using each comparison operator.
- Write a statement using each logical operator.


String Formatting

Welcome back, string wranglers!

Strings in Python are not just sequences of characters; they are sequences with superpowers. And one of these powers is formatting. With string formatting, we can create text with variable content.

Formatting with the format() method:
- This method lets us insert values into a string.
  Example:
    name = "World"
    greeting = "Hello, {}!".format(name)
    print(greeting)  # This will print "Hello, World!"

f-Strings:
- A newer and even more convenient way to format strings is using f-strings (available from Python 3.6+).
  Example:
    name = "World"
    greeting = f"Hello, {name}!"
    print(greeting)  # This will print "Hello, World!"

Exercise:
- Create a string that includes at least two placeholders and use format() to insert values into them.
- Do the same with an f-string.



Loops

Ahoy loop lovers!

Loops are the way to do something over and over again in Python. There are two main types of loops: "for" loops and "while" loops.

For Loops:
- Use a for loop when you know how many times you want to repeat an action.
  Example:
    for i in range(5):
        print(i)  # This will print numbers 0 to 4, each on a new line.

While Loops:
- Use a while loop when you want to continue until a certain condition is no longer true.
  Example:
    i = 0
    while i < 5:
        print(i)
        i += 1  # This will also print numbers 0 to 4, each on a new line.

Exercise:
- Write a for loop that prints your name 10 times.
- Write a while loop that counts down from 10 to 1.



Conditions

Greetings, decision-makers

Conditions are how we make decisions in programming. By evaluating conditions, we can tell our program to execute certain code when the condition is true, and other code when it is false.

If Statements:
- The 'if' statement is your bread and butter for decision-making.
  Example:
    age = 18
    if age >= 18:
        print("You can vote.")
    else:
        print("You are too young to vote.")

Elif:
- 'elif' stands for 'else if'. It's used to check multiple expressions for TRUE and execute a block of code as soon as one of the conditions evaluates to TRUE.
  Example:
    if age < 18:
        print("You are too young to vote.")
    elif age >= 18:
        print("You can vote.")

Nested If Statements:
- You can place an 'if' statement inside another 'if' statement to check for another condition.
  Example:
    if age >= 18:
        if age >= 35:
            print("You can run for president.")
        else:
            print("You can vote but not run for president.")

Exercise:
- Write an if statement that checks if a number is positive, negative, or zero.
- Add an elif to check if the number is even or odd.



Functions and Objects

Salutations, function followers and object enthusiasts!

Functions are blocks of code that perform a specific task, and objects are instances of classes that can hold data and have functions associated with them.

Defining Functions:
- To define a function, use the 'def' keyword, followed by the function name and parentheses ().
  Example:
    def greet(name):
        return "Hello, " + name + "!"

Calling Functions:
- After defining a function, you can call it by using its name followed by parentheses.
  Example:
    message = greet("Alice")
    print(message)  # This will print "Hello, Alice!"

Objects and Classes:
- A class is a blueprint for objects. An object is an instantiation of a class.
  Example:
    class Car:
        def __init__(self, color, brand):
            self.color = color
            self.brand = brand

        def display_info(self):
            return "This is a " + self.color + " " + self.brand + "."

    my_car = Car("red", "Toyota")
    print(my_car.display_info())  # This will print "This is a red Toyota."

Exercise:
- Write a function that calculates and returns the area of a rectangle.
- Define a class called 'Animal' with a method that prints "This is an animal".



Dictionaries

Welcome, key-value pair collectors!

Dictionaries in Python are another form of data structure that allows us to store data in key-value pairs.

Creating a Dictionary:
- Use curly braces {} to create a dictionary. Separate keys from values with a colon :, and items with commas.
  Example:
    my_dict = {'name': 'John', 'age': 30}
    print(my_dict)

Accessing Dictionary Values:
- You access dictionary values by using their keys.
  Example:
    print(my_dict['name'])  # This will print 'John'.

Adding and Removing Keys:
- You can add new key-value pairs or remove existing ones.
  Example:
    my_dict['email'] = 'john@example.com'  # Add a new key-value pair.
    del my_dict['age']  # Remove the key 'age' and its value.

Exercise:
- Create a dictionary representing a book, with keys like 'title', 'author', and 'year'.
- Add a key for 'ISBN' and remove the 'year' key.



Modules and Packages

Hello, modular programmers and package gatherers!

Modules and packages in Python are ways of organizing and reusing code. Think of a module as a file containing Python definitions and statements, and a package as a directory of modules.

Importing Modules:
- You can use modules by importing them into your scripts.
  Example:
    import math
    print(math.sqrt(16))  # This will print '4.0'.

Creating and Using Packages:
- You can create your own packages by creating a directory with a special file named '__init__.py'.
  Example:
    # Assume 'my_package' is a directory with '__init__.py' and 'module.py' inside it.
    from my_package import module
    module.my_function()

Exercise:
- Import the 'random' module and use it to generate a random number.
- Create a simple package with one module and use a function from that module in your script.

This wraps up our journey through Python basics. Keep experimenting and exploring, and remember that every expert was once a beginner. Happy coding!



Advanced Tutorials

List Comprehensions

Welcome to our exploration of list comprehensions in Python—an elegant twist on creating lists. Today, we'll replace our usual list-building loops with this succinct and powerful construct. By embracing list comprehensions, we're aiming for cleaner, more Pythonic code. Together, we'll learn to encapsulate complex ideas in a single line, enhancing both readability and efficiency. Get ready to add this refined technique to your Python repertoire.

Creating a List Comprehension:
- Use brackets containing an expression followed by a `for` clause, then zero or more `for` or `if` clauses.
  Example:
    squares = [x**2 for x in range(10)]

Exercise:
- Create a list comprehension that contains the cubes of all even numbers from 0 to 20.




Generators

Today, we dive into the world of Python generators, a robust feature for managing sequences. Generators allow us to iterate over data without the memory constraints of lists, providing an efficient way to handle large data streams. We'll learn to declare generator expressions and functions, harnessing their laziness—generating items on-the-fly. This session is all about enhancing performance and optimizing our Python code. Get ready to unlock the potential of generators and streamline your programming workflow

Creating a Generator:
- Use parentheses to create a generator expression.
  Example:
    my_generator = (x**2 for x in range(10))

Exercise:
- Write a generator expression that generates the factorial of numbers from 1 to 10. Use a library function for factorial calculation.



Lambda Functions

Lambda functions, the language's approach to anonymous, inline functions. These one-liners are not only about brevity but also about functional elegance. We'll explore how to create and utilize these concise functions for quick, throwaway operations without the need for formal def statements. Perfect for small-scale tasks, lambda functions promote cleaner and more efficient code. Prepare to embrace the simplicity and power of Python's lambda functions.

Creating a Lambda Function:
- Use the `lambda` keyword.
  Example:
    multiply = lambda x, y: x * y

Exercise:
- Write a lambda function that reverses a string and use it to reverse the word 'hello'.



Multiple Function Arguments

Today's focus shifts to Python's flexibility with function arguments, where we tackle the challenge of handling multiple inputs. We'll navigate the dynamic use of *args and **kwargs, which allow our functions to accept arbitrary numbers of positional and keyword arguments. This powerful feature lends our code remarkable flexibility, enabling it to adapt to a variety of inputs with ease. Get ready to learn how to write functions that aren't just versatile but also inclusive of any number of arguments.

Defining Functions with Multiple Arguments:
- Use *args and **kwargs to accept a variable number of arguments.
  Example:
    def many_args(*args, **kwargs): pass

Exercise:
- Create a function that accepts any number of numeric arguments and returns the sum.



Regular Expressions

Today, we delve into the world of Regular Expressions in Python, a vital skill for advanced string manipulation and pattern matching. Regular Expressions, or 'regex', provide a robust toolkit for searching, matching, and manipulating text. We'll learn to harness the power of Python's re module, exploring patterns that can match complex string scenarios. This session is your gateway to understanding how regex can make text processing more efficient and sophisticated. Prepare to unlock the secrets of effective string handling with regular expressions.

Using Regular Expressions:
- Use the `re` module to work with Regular Expressions.
  Example:
    import re
    pattern = r"\d+"

Exercise:
- Write a regular expression that matches email addresses and use it to find all emails in a given string.



Exception Handling

In our upcoming Python session, we turn our attention to Exception Handling, an essential aspect of writing robust and error-resistant code. We'll explore the art of gracefully managing unexpected situations using try and except blocks. This session aims to equip you with the skills to predict and handle errors, ensuring your programs run smoothly under various conditions. Understanding Exception Handling is key to advancing from a novice to a seasoned Python programmer. Prepare to learn how to make your code not just functional, but also resilient and reliable.

Handling Exceptions:
- Use `try` and `except` blocks.
  Example:
    try: pass
    except ZeroDivisionError: pass

Exercise:
- Write a function that divides two numbers, handle the case where the denominator is zero.



Serialization

Today's Python session introduces us to Serialization, a crucial concept for storing and transmitting complex data structures. We'll dive into how Python's json and pickle modules enable us to convert Python objects to a storable and transportable format, and vice versa. This process is vital for data persistence, API interactions, and deep data manipulation. By mastering serialization, you'll gain the ability to maintain the state and integrity of your data across various platforms and uses. Get ready to explore the transformative power of serialization in Python.

Using Serialization with JSON:
- Use the `json` module.
  Example:
    import json
    data = {'name': 'John'}

Exercise:
- Serialize a dictionary containing a list of numbers 1-10 into JSON, then deserialize it back into Python.



Partial Functions

In our next Python tutorial, we'll explore the concept of Partial Functions, an elegant tool for function customization. Partial functions in Python allow us to 'fix' certain arguments of a function, creating new variants with fewer parameters. This session will guide you through using the functools.partial to create these tailored function versions, enhancing code reusability and efficiency. By learning about partial functions, you'll add another level of sophistication to your Python programming skills. Prepare to simplify complex function calls and streamline your code with partial functions.

Creating Partial Functions:
- Use the `functools.partial` function.
  Example:
    from functools import partial

Exercise:
- Create a partial function that multiplies any number by 10.



Code Introspection

Welcome to our exploration of Code Introspection in Python, a powerful feature that allows for deep self-examination of code at runtime. This session will unveil how introspection provides insights into objects, classes, and functions, enabling us to probe their properties and behaviors dynamically. We'll delve into the utilities like type(), dir(), id(), and getattr() to unravel the mysteries within our code. Grasping code introspection is a step towards mastering Python, as it offers a window into the inner workings of the language. Get ready to enhance your debugging and development skills with the art of introspection.


Exploring Introspection:
- Use functions like `type()`, `dir()`, `id()`, `getattr()`.
  Example:
    my_list = [1, 2, 3]

Exercise:
- Use introspection to list all the methods of a string object and find one that checks if the string is alphanumeric.



Closures

Today, we journey into the concept of Closures in Python, a subtle yet powerful feature of function scoping. Closures provide a way for a function to retain access to its enclosing scope's variables, even after that scope has completed execution. In this session, we'll explore how closures capture and maintain state in a function, leading to elegant and efficient code designs. Understanding closures will deepen your grasp of Python's function behavior and scope management. Prepare to unlock the potential of closures and their practical applications in your Python projects.

Understanding Closures:
- A function with an environment.
  Example:
    def outer_func(x): pass

Exercise:
- Write a closure that encapsulates a counter function which increments by 1 each time it's called.



Decorators

Welcome to our exploration of Decorators in Python, an instrumental feature for enhancing and modifying the behavior of functions. Decorators provide a unique way to add functionality to existing code without altering its structure, offering a clear path to more maintainable and expressive code. In this session, we'll learn how to write our own decorators and understand how they can be used to extend the capabilities of functions elegantly. This powerful tool will not only refine your coding skills but also introduce you to advanced concepts of Python programming. Get ready to dive into the dynamic world of decorators and discover how they can transform the way you write functions

Creating Decorators:
- A function that takes another function.
  Example:
    def my_decorator(func): pass

Exercise:
- Write a decorator that measures the execution time of a function.



Map, Filter, Reduce

Today's session delves into the functional programming aspects of Python with Map, Filter, and Reduce. These three functions embody a powerful approach to processing collections, allowing for concise and expressive manipulation of data. We'll explore how map transforms, filter selects, and reduce aggregates elements of sequences, simplifying complex operations into elegant, one-liner solutions. By mastering these functions, you'll add efficiency and clarity to your data processing tasks. Prepare to harness these functional tools and elevate your Python coding prowess.

Using Map, Filter, and Reduce:
- Use `map()`, `filter()`, and `reduce()` for functional programming.
  Example:
    from functools import reduce

Exercise:
- Use map to create a list of the names of the numbers from 1 to 5, filter to get only the names that have more than 3 letters, and reduce to concatenate them into a single string.

End of Advanced Tutorials
