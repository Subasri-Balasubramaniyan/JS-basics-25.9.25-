🔹 1. Variables

Variables are used to store data values.

var → Function scoped (old, avoid in modern JS).

let → Block scoped, can be reassigned.

const → Block scoped, cannot be reassigned.

var city = "Nagapattinam";
let age = 22;
const country = "India";

🔹 2. Data Types

JavaScript has two types:

Primitive Types

String → "Hello"

Number → 10, 3.14

Boolean → true / false

Null → null

Undefined → undefined

BigInt → 123n

Symbol → Symbol("id")

Non-Primitive Types

Object

Array

Function

let str = "Subasri";        // String
let num = 25;               // Number
let isStudent = true;       // Boolean
let nothing = null;         // Null
let notDefined;             // Undefined
let arr = [1, 2, 3];        // Array
let obj = { name: "Subasri", age: 22 }; // Object

🔹 3. Operators

Operators perform operations on values.

Arithmetic: +, -, *, /, %, ++, --

Comparison: ==, ===, !=, <, >, <=, >=

Logical: &&, ||, !

Assignment: =, +=, -=, *=, /=

let x = 10, y = 5;
console.log(x + y);  // 15
console.log(x === 10); // true
console.log(x > 5 && y < 10); // true

🔹 4. Functions

Functions are reusable blocks of code.

// Function Declaration
function greet(name) {
  return "Hello, " + name;
}
console.log(greet("Subasri")); // Hello, Subasri

// Arrow Function
const add = (a, b) => a + b;
console.log(add(5, 3)); // 8

🔹 5. Conditional Statements

Used for decision-making.

let marks = 80;

if (marks >= 90) {
  console.log("Grade A");
} else if (marks >= 75) {
  console.log("Grade B");
} else {
  console.log("Grade C");
}

// Switch Example
let day = "Monday";
switch(day) {
  case "Monday":
    console.log("Start of the week");
    break;
  case "Friday":
    console.log("Weekend is coming!");
    break;
  default:
    console.log("Regular day");
}
