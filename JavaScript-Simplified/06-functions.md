# Functions
Functions are used for creating logic and we don’t have to write the same code multiple times. In JavaScript, we can create functions simply by typing **function** (all lower case) and give the function a name kind of like a variable and end it with a parentheses “()” symbol which contains all the required arguments for a given function to run. And finally, add a pair of curly braces “{}” that will contain the code that you want to execute when the function runs.

```jsx

function helloWorld(){

console.log("Hello world")

} //This is how you create a simple function in JavaScript

```

Now, if we want to execute our function we simply call it by using its name along with the parentheses wherever we want in our code.

```jsx

function helloWorld(){

console.log("Hello world")

} //This is how you create a simple function in JavaScript

  

helloWorld() //This will call the function and print out the string.

```

Functions that take arguments or parameters in them allow us to create complex functions that can perform any type of operation that you want.

```jsx

function Sum(a, b){

console.log(a + b)

}

Sum(1,2); // This will print out the number three.

```

In the above code snippet when we call the sum function it will display the number three in the console because we created the function to accept two arguments and then add them together in the body of the function. Now, when we call it and pass in the values the number one represents argument **a** and the number two represents argument **b** and the result of adding these two will be the number three so it is printed out in the console.

We can also use external variables as arguments and our function will perform the same way it was performing before.

```jsx

function Sum(a, b){

console.log(a + b)

}

let x = 2

let y = 5

Sum(x,y); // This will print out the sum of these variables.

```

You might have noticed that we are only logging out values to the console. But if we wanted to use them for something other than that we use a keyword called to return. We can use the return keyword to output anything we want from a function. For now, let’s return the output of the sum function.

```jsx

function Sum(a, b){

return a + b

}

let x = 2

let y = 5

Sum(x,y);

```

You won’t be able to see anything on your console now because we aren’t logging anything to it we are just returning the value of the sum function we haven’t logged out the result yet. Keep in mind that we are only returning the summed value of variables x and y in the above code snippet. We can assign a variable to the summed value so that we can use the variable later on in our code.

```jsx

function Sum(a, b){

return a + b

}

let x = 2

let y = 5

let ans = Sum(x,y)

```

In the above code snippet, we assigned a variable the value of the sum function, we can now easily use the variable anywhere we want in our code to get the value of the sum function. If we pass the variable that we assigned to the sum function in console log it will display the value of the sum function.

```jsx

function Sum(a, b){

return a + b

}

let x = 2

let y = 5

let ans = Sum(x,y)

console.log(ans) //This will display the value of the sum function in your console.

```
