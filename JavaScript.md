# Complete Guide to JavaScript for Beginners

## Introduction
JavaScript (JS) is a versatile programming language used to add interactivity to websites. It runs in the browser and is essential for modern web development.

## JavaScript Basics

### JavaScript Syntax
```js
// Single-line comment
/* Multi-line comment */

// Variables
var x = 10; // Old way (not recommended)
let y = 20; // Block-scoped variable
const z = 30; // Immutable variable
```

### Data Types
```js
let num = 5; // Number
let text = "Hello"; // String
let isTrue = true; // Boolean
let items = [1, 2, 3]; // Array
let person = {name: "John", age: 25}; // Object
let notDefined; // Undefined
let emptyValue = null; // Null
```

### Type Checking
```js
console.log(typeof 10); // "number"
console.log(typeof "Hello"); // "string"
console.log(typeof true); // "boolean"
```

## Operators
### Arithmetic Operators
```js
let sum = 5 + 3; // Addition
let diff = 10 - 4; // Subtraction
let product = 2 * 3; // Multiplication
let quotient = 10 / 2; // Division
let remainder = 10 % 3; // Modulus
let power = 2 ** 3; // Exponentiation
```
### Comparison Operators
```js
console.log(5 > 3);  // true
console.log(5 == "5"); // true (loose equality)
console.log(5 === "5"); // false (strict equality)
```

## Control Flow
### Conditional Statements
```js
if (x > 10) {
    console.log("x is greater than 10");
} else if (x === 10) {
    console.log("x is exactly 10");
} else {
    console.log("x is less than 10");
}
```

### Switch Statement
```js
switch (fruit) {
    case "apple":
        console.log("This is an apple");
        break;
    case "banana":
        console.log("This is a banana");
        break;
    default:
        console.log("Unknown fruit");
}
```

## Loops
### For Loop
```js
for (let i = 0; i < 5; i++) {
    console.log(i);
}
```
### While Loop
```js
let i = 0;
while (i < 5) {
    console.log(i);
    i++;
}
```

## Functions
### Function Declaration
```js
function greet(name) {
    return "Hello, " + name;
}
console.log(greet("Alice"));
```
### Arrow Functions
```js
const add = (a, b) => a + b;
console.log(add(2, 3));
```

## Arrays
```js
let fruits = ["Apple", "Banana", "Mango"];
console.log(fruits[0]); // Access element
fruits.push("Orange"); // Add element
fruits.pop(); // Remove last element
```

## Objects
```js
let person = {
    name: "John",
    age: 30,
    greet: function() {
        return "Hello " + this.name;
    }
};
console.log(person.greet());
```

## DOM Manipulation
```js
// Selecting elements
let heading = document.getElementById("title");
let buttons = document.querySelectorAll("button");

// Changing content
heading.innerText = "New Title";

// Adding event listener
buttons[0].addEventListener("click", () => {
    alert("Button clicked!");
});
```

## Event Handling
```js
document.getElementById("btn").addEventListener("click", function() {
    console.log("Button clicked!");
});
```

## ES6 Features
### Template Literals
```js
let name = "Alice";
console.log(`Hello, ${name}!`);
```
### Destructuring
```js
let [a, b] = [10, 20];
let {name, age} = person;
```
### Spread Operator
```js
let arr1 = [1, 2, 3];
let arr2 = [...arr1, 4, 5];
console.log(arr2);
```

## Promises & Async/Await
```js
function fetchData() {
    return new Promise((resolve) => {
        setTimeout(() => resolve("Data fetched"), 2000);
    });
}
async function getData() {
    let data = await fetchData();
    console.log(data);
}
getData();
```

## Error Handling
```js
try {
    let result = 10 / 0;
    if (!isFinite(result)) throw "Cannot divide by zero";
} catch (error) {
    console.log("Error:", error);
} finally {
    console.log("Execution completed");
}
```

## Local Storage & Session Storage
```js
// Local Storage
localStorage.setItem("username", "JohnDoe");
console.log(localStorage.getItem("username"));
localStorage.removeItem("username");

// Session Storage
sessionStorage.setItem("sessionUser", "JaneDoe");
console.log(sessionStorage.getItem("sessionUser"));
sessionStorage.clear();
```

## Conclusion
This guide covers fundamental JavaScript concepts, including syntax, loops, functions, objects, ES6 features, error handling, and storage. Keep practicing and exploring more to master JavaScript!

