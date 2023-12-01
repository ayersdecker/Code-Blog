---
title: C#
layout: default
---

# **C#**
An object-oriented, component-oriented programming language. C# provides language constructs to directly support these concepts, making C# a natural language in which to create and use software components. Since its origin, C# has added features to support new workloads and emerging software design practices.  *-Microsoft*

C# is used within a variety of ways, most commonly in Game Development like Unity, and  .NET Frameworks such as Xamarin, MAUI, UWP, ASP.NET. Syntactically, C# is akin to other popular languages like C/C++ and Java, but without the need to manage memory or difficult-to-gather packages. C# is a statically-typed language, meaning that the code must first run through a C# Compiler before it can run. This helps weed out major errors, and speeds up the performance of the final product. Being a high-level langauge, C# can do almost anything required for complex tasks, but is not as efficient when it comes writing scripts or small tasks. 

Though not the most popular language on the market, there are still quite a few jobs hiring for .NET or game developers. If you are interested in building Desktop, Mobile, Web, PWAs, ML, or Gaming applications, C# is the language for you. 

## Tools for Developing
The recommended IDE for C# is [Visual Studio 2022](https://visualstudio.microsoft.com/vs/)<br>
Visual Studios is Microsoft's dedicated IDE for complex software development, and is best suited for developing C#, C/C++, and Python. It supports more languages as well, but not as well as these listed here.

Alternatively, [Visual Studio Code](https://code.visualstudio.com/download) or [JetBrains Rider](https://www.jetbrains.com/rider/) will also provide great tools for C# development. IDE selection is mostly about supported features and personal preference. 

.NET can be developed on Windows, MacOS, and popular Linux distributions such as Debian and Ubuntu. 


## Basic Datatypes

### String
```
string firstName = "Decker";
```
A string of charaters, textual data
<br>
### Integer
```
int age = 30;
```
Represents whole numbers without any fractional or decimal part.
<br>
### Double
```
double salary = 55000.50;
```
Represents floating-point numbers, including decimal fractions.
<br>
### Boolean
```
bool isStudent = true;
```
Represents a binary choice, typically used for true/false conditions.
<br>
### Char
```
char grade = 'A';
```
Represents a single Unicode character.
<br><br>

## Control Flow
### If Statement
```
if (age > 18)
{
    Console.WriteLine("You are an adult.");
}
else
{
    Console.WriteLine("You are a minor.");
}
```
<br>
Executes a block of code based on a conditional expression.

### For Loop
```
for (int i = 0; i < 5; i++)
{
    Console.WriteLine(i);
}
```
Repeats a block of code a specified number of times.

### While Loop
```
int count = 0;
while (count < 3)
{
    Console.WriteLine("Count: " + count);
    count++;
}
```
Repeats a block of code while a specified condition is true.

### Methods
```
public int Add(int a, int b)
{
    return a + b;
}

int result = Add(5, 3);
Console.WriteLine(result); // Output: 8
```
Defines a function named Add that takes two parameters and returns their sum.<br><br>

### Classes and Objects
```public class Person
{
    public string Name { get; set; }
    public int Age { get; set; }

    public void DisplayInfo()
    {
        Console.WriteLine($"Name: {Name}, Age: {Age}");
    }
}
Person person1 = new Person();
person1.Name = "John";
person1.Age = 25;
person1.DisplayInfo();
```
Defines a class Person with properties and a method. Creates an instance of the class and uses it to display information.
