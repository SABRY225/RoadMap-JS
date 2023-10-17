# JavaScript Loop
JavaScript supports different kinds of loops:
```
for - loops through a block of code a number of times
for/in - loops through the properties of an object
for/of - loops through the values of an iterable object
while - loops through a block of code while a specified condition is true
do/while - also loops through a block of code while a specified condition is true
Break and Continue
```
## The For Loop
```
The for statement creates a loop with 3 optional expressions:

Syntax
for (expression 1; expression 2; expression 3) {
  // code block to be executed
}
```
## The For In Loop
```
The JavaScript for in statement loops through the properties of an Object:

Syntax
for (key in object) {
  // code block to be executed
}

Example
const person = {fname:"John", lname:"Doe", age:25};

let text = "";
for (let x in person) {
  text += person[x];
}
```
#### For In Over Arrays
```
The JavaScript for in statement can also loop over the properties of an Array:

Syntax
for (variable in array) {
  code
}

const numbers = [45, 4, 9, 16, 25];

let txt = "";
for (let x in numbers) {
  txt += numbers[x];
}
```
#### Array.forEach()
```
The forEach() method calls a function (a callback function) once for each array element.

Example
const numbers = [45, 4, 9, 16, 25];

let txt = "";
numbers.forEach(myFunction);

function myFunction(value, index, array) {
  txt += value;
}
```
## The For Of Loop
```
The JavaScript for of statement loops through the values of an iterable object.

It lets you loop over iterable data structures such as Arrays, Strings, Maps, NodeLists, and more:

Syntax
for (variable of iterable) {
  // code block to be executed
}
```
## The While Loop
```
The while loop loops through a block of code as long as a specified condition is true.

Syntax
while (condition) {
  // code block to be executed
}

Example
while (i < 10) {
  text += "The number is " + i;
  i++;
}
``` 
## The Do While Loop
```
The do while loop is a variant of the while loop. This loop will execute the code block once, before checking if the condition is true, then it will repeat the loop as long as the condition is true.

Syntax
do {
  // code block to be executed
}
while (condition);

Example
do {
  text += "The number is " + i;
  i++;
}
while (i < 10);
``` 
## The Break Statement
```
You have already seen the break statement used in an earlier chapter of this tutorial. It was used to "jump out" of a switch() statement.

The break statement can also be used to jump out of a loop:

Example
for (let i = 0; i < 10; i++) {
  if (i === 3) { break; }
  text += "The number is " + i + "<br>";
}
```
## The Continue Statement
```
The continue statement breaks one iteration (in the loop), if a specified condition occurs, and continues with the next iteration in the loop.

This example skips the value of 3:

Example
for (let i = 0; i < 10; i++) {
  if (i === 3) { continue; }
  text += "The number is " + i + "<br>";
}
```