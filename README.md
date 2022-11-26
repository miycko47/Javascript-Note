# Javascript Notes.

## What is javascript?

- JavaScript (JS) is a lightweight, interpreted, or just-in-time compiled programming language with first-class functions. While it is most well-known as the scripting language for Web pages, many non-browser environments also use it, such as Node.js, Apache CouchDB and Adobe Acrobat. JavaScript is a prototype-based, multi-paradigm, single-threaded, dynamic language, supporting object-oriented, imperative, and declarative (e.g. functional programming) styles.

## Variables.

* Variables are containers for storing data (storing data values).
* On this block of code x, y and z are declared with the "var" keyword.
```
var x = 5;
var y = 6;
var z = x + y;
```

## Datatype.
There are different types of data that we can use in a JavaScript program. For example,
```
const x = 5;
const y = "Hello";
Here,
```
5 is an integer data.
"Hello" is a string data.

## Conditional statement.

In JavaScript we have the following conditional statements:

- Use if to specify a block of code to be executed, if a specified condition is true
- Use else to specify a block of code to be executed, if the same condition is false
- Use else if to specify a new condition to test, if the first condition is false
- Use switch to specify many alternative blocks of code to be executed

### The if statmnet.
Use the if statement to specify a block of JavaScript code to be executed if a condition is true.
```
if (hour < 18) {
  greeting = "Good day";
}
```
### The else Statement.
Use the else statement to specify a block of code to be executed if the condition is false.
```
if (hour < 18) {
  greeting = "Good day";
} else {
  greeting = "Good evening";
}
```
### The else if Statement.
Use the else if statement to specify a new condition if the first condition is false.
```
if (time < 10) {
  greeting = "Good morning";
} else if (time < 20) {
  greeting = "Good day";
} else {
  greeting = "Good evening";
}
```
## Loops.

- Loops are used in JavaScript to perform repeated tasks based on a condition. Conditions typically return true or false. A loop will continue running until the defined condition returns false.
- Instead of writing:
```
text += cars[0] + "<br>";
text += cars[1] + "<br>";
text += cars[2] + "<br>";
text += cars[3] + "<br>";
text += cars[4] + "<br>";
text += cars[5] + "<br>";
```
- You can write:
```
for (let i = 0; i < cars.length; i++) {
  text += cars[i] + "<br>";
}
```
### The for loop
The for statement creates a loop with 3 optional expressions:
```
for (expression 1; expression 2; expression 3) {
  // code block to be executed
}
```
#### Expression 1 is executed (one time) before the execution of the code block.

#### Expression 2 defines the condition for executing the code block.

####Expression 3 is executed (every time) after the code block has been executed.
## Methods.

## DOM

## Events.



