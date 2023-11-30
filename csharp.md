---
title: C#
layout: default
---

# C#
An object-oriented, component-oriented programming language. C# provides language constructs to directly support these concepts, making C# a natural language in which to create and use software components. Since its origin, C# has added features to support new workloads and emerging software design practices. *-Microsoft*

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
