# Closures:
Closures in JavaScript are what we call a function inside of a function, which we have learned about before.

```jsx

let a = 1

function func(){

console.log(a)

}

a = 2

//This will print out the value of 2 because of scope and hosting,

//this entire code is a clousre.

```

Closures are essentially a function that is inside of another function, we will now look at the textbook example of a closure

```jsx

function print(variable){

return function func(variable2){

console.log(variable)

console.log(variable2)

}

}

let a = print(1)

a(2)

/*This is an example of a closure in which we pass a function

inside of another function */

```
