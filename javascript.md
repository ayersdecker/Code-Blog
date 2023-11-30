---
title: Javascript
layout: default
---
# **Javascript**
JavaScript is a programming language that is used to add interactivity to web pages. It is a client-side language, which means that it is executed on the user's computer, not on the server. JavaScript can be used to create a variety of effects, such as animations, pop-ups, and form validation.

## Primative Types

### Immutable Declaration
```const name = 'Decker';```<br><br>
When a value is designed not to be changed/mutated

### Mutatable Declaration 
``` let age = 23; ```<br>
``` age = 24; ```<br><br>
When a value is designed to accomadate changes/mutations

### String Literal
``` const name = 'Decker'; ```<br><br>
A group of characters meant to be displayed without computational qualities, i.e. textual information

### Number Literal
``` const numOfSiblings = 1; ```<br><br>
A numerical value, of some sort, meant to be computable or mathmatically governed

### Boolean Literal
``` const isAlive = true; ```<br><br>
A true/false statement, or condition in where there is only 2 outcomes available

### Undefined and Null
``` name = undefined ```<br><br>
Most common way to "reset" a value without a default. No value at a particular address<br><br>
``` name = null ``` <br><br>
Strong declaration to remove any value from the address

## Reference Types

### Object
```  
let person = {
      name: 'Decker',
      age:  24
};
```
This Object was created using ```{}```, then was filled with properties using ```,``` to separate each key value pair

``` let myName = person.name; ```
Properties from objects can be used by typing the objects name, a period, and the property name. i.e. ```objectName.property```

### Array
```
let favoriteMovies = ['Blade Runner', 'Blade Runner 2049', 'Interstellar', 'Tron Legacy'];
let topFavoriteMovie = favoriteMovies[1];
```
An array is made using ```[]```. The array above is filled with strings of my favorite movies<br><br> 
I selected an item from the array using ```favoriteMovies[1]```, indicating I wanted the item from the second address

### Function
```
function addNums(firstNum, secondNum){
   return firstNum + secondNum;
}
```
A function is declared using the ```function``` keyword, a name for the function, parameters inside of ```()```, and finally ```{}```<br><br>
Here's a quick template ```function myFunction(parameter){ }```<br><br>
Functions also have some included keywords that can be used inside of them, the most common being ```return```, meant to return a value back to the function call-line