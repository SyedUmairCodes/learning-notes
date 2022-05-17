# Hoisting:
We are now going to learn a very simple topic called Hoisting. How hoisting works in JavaScript is from top to bottom. If we have a function that takes two arguments and adds them together and we call that function then we have a variable with a given value and we use that variable as an argument when we call our function it won’t work and it will give a reference error saying that it cannot access the value of the variable because it is initialized after the function call.

```jsx

function sum(a,b){

return a + b}

sum(1,2)

sum (a,2) //We are calling the function before declaring the variable

  

let a = 1

```

Hoisting a function is different than hoisting a variable, we create a function and call it above the function and it will work. This may be confusing to you because we are using the function before defining it.

```jsx

console.log(sum(1,2))

  

function sum(a,b){

return a + b

}

//This will work without any errors.

```

The reason for the above code snippet to run without any problems is that before JavaScript checks your code from top to bottom it does a very interesting step It will take all of the functions that you have written and place them on the top of the file and pretends that they are written there. This is what hoisting does, it takes your functions (wherever you have written them) and moves them to the top of the file when it runs your code.

An interesting thing to note about hoisting in JavaScript is that it will only work with the normal functions and not arrow functions.

```jsx

console.log(sum(1,2))

  

let sum = (a,b) => {

return a + b

}

//This will give you a reference error in the console.

```

Hoisting does not work with arrow functions because arrow functions are defined as variables and you cannot hoist variables as we have seen above.