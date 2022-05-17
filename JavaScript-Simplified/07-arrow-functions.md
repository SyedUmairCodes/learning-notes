# Arrow Functions:
Arrow functions and normal functions in JavaScript are similar in most aspects but different in how we write them. When creating an arrow function you don’t write the **function** keyword. We define a variable instead and then make it equal to the arguments that we need to pass in the function then we create an arrow sign(⇒) using the equals and greater than symbol and finish it off by opening and closing the curly braces. What the arrow sign means is to take the arguments in the parentheses and then run the code defined in the curly braces.

```jsx

function myName( name ){ console.log("Jhon") } //This is a normal function.

  

let myName( name ) => { console.log("Jhon") } //This is an arrow function.

```

One thing that is unique about arrow functions is that if you are returning only a single line in the code block you don’t need to type in the return keyword or the curly braces when using arrow functions.

```jsx

function func( a, b ){ return a + b } //This is a normal function.

  

let func( a, b ) => a + b //This is an arrow function.

```

The biggest advantage of arrow functions is when you are passing a function to another function because write less code when using arrow functions. When creating anonymous functions using arrow functions you just need the parentheses and the arrow symbol Which results in less code being written.