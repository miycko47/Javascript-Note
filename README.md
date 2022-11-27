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

#### Expression 3 is executed (every time) after the code block has been executed.

## Methods.
Methods can be defined in various ways:
```
const person = {
  firstName: "John",
  lastName: "Doe",
  id: 5566,
  fullName: function() {
    return this.firstName + " " + this.lastName;
  }
};
```
##### In JavaScript, the "this" keyword refers to an object.
- In an object method, this refers to the object.
- Alone, this refers to the global object.
- In a function, this refers to the global object.
- In a function, in strict mode, this is undefined.
- In an event, this refers to the element that received the event.
- Methods like call(), apply(), and bind() can refer this to any object.
## DOM
- The DOM is a W3C (World Wide Web Consortium) standard.

- The DOM defines a standard for accessing documents:

"The W3C Document Object Model (DOM) is a platform and language-neutral interface that allows programs and scripts to dynamically access and update the content, structure, and style of a document."

- The W3C DOM standard is separated into 3 different parts:

- Core DOM - standard model for all document types
- XML DOM - standard model for XML documents
- HTML DOM - standard model for HTML documents
### The DOM Programming Interface
The HTML DOM can be accessed with JavaScript (and with other programming languages).

In the DOM, all HTML elements are defined as objects.

The programming interface is the properties and methods of each object.

A property is a value that you can get or set (like changing the content of an HTML element).

A method is an action you can do (like add or deleting an HTML element).

- The following example changes the content (the innerHTML) of the <p> element with id="demo":
```
<html>
<body>

<p id="demo"></p>

<script>
document.getElementById("demo").innerHTML = "Hello World!";
</script>

</body>
</html>
```

## Events.
### HTML Events
  An HTML event can be something the browser does, or something a user does.

Here are some examples of HTML events:

An HTML web page has finished loading
An HTML input field was changed
An HTML button was clicked
Often, when events happen, you may want to do something.

JavaScript lets you execute code when events are detected.

HTML allows event handler attributes, with JavaScript code, to be added to HTML elements.
  
With single quotes:
```
  <element event='some JavaScript'>
```

