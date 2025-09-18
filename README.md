1) Difference between var, let, and const

1 var: Function-scoped, can be re-declared and reassigned, hoisted with undefined. Mostly used in old JavaScript.
2 let`: Block-scoped, can be reassigned but not re-declared in the same scope. Safer than var.
3 const: Block-scoped, cannot be reassigned or re-declared. Best for constants and fixed references.


2) Difference between map(), forEach(), and filter()**

1 map(): Creates a new array by transforming each element.
2 forEach(): Loops through each element, executes a function, but doesn’t return a new array.
3 filter(): Returns a new array containing only elements that satisfy a condition.

Example:

js
const nums = [1,2,3,4];
nums.map(n => n*2);     // [2,4,6,8]
nums.forEach(n => console.log(n)); // prints 1,2,3,4
nums.filter(n => n%2===0); // [2,4]


3) Arrow Functions in ES6
Arrow functions provide a shorter syntax for writing functions.

1 Don’t have their own this, they use the parent’s this.
2 Cannot be used as constructors.
3 Cleaner and more concise.

js
const add = (a, b) => a + b;


4) Destructuring Assignment in ES6
Allows unpacking values from arrays or objects directly into variables.

1 Makes code shorter and easier to read.

js
const [x, y] = [10, 20];  
const {name, age} = {name: "Alice", age: 25};  



5) Template Literals in ES6
Template literals use backticks (  ) and support variable interpolation with ${}.

1 Easier than string concatenation.
2 Can span multiple lines.

js
const name = "John";  
const age = 30;  
console.log(My name is ${name} and I am ${age} years old.);  



