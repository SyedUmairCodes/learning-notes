# Pass a function to another function:
We have learned about passing arguments and the basics of functions. Now, we will learn how to pass a function as an argument to another function. This is a very important topic while learning JavaScript because sometimes even professionals get confused with this.

Create a simple function that takes a variable and prints it out when we call it. It’s a simple function that just prints out any argument that we pass it.

```jsx

function helloWorld(variable){

console.log(variable)

}

helloWorld("Hello World!") //This will print out the value given in the parentheses.

```

What if instead of passing “Hello World!” we just console log the function itself when we are calling it.

```jsx

function helloWorld(variable){

console.log(variable)

}

console.log(helloWorld)

```

If we run the above code snippet it will print out the definition of the function marked with an *f* showing that this is a function. When we create a function the name of that function acts as a variable that we later call in our code. So we can use the function name as a variable inside another function. These types of functions are also called callback functions.

Create a function that takes three arguments, two variables, and one callback. normally you will just return the value of the variables but instead of that we also have a callback. so we are going to pass in the sum of the two variables in the callback.

```jsx

function sum(a,b,callback){

callback(a + b)

}

```

Now, we create another function that is going to take the sum of the two variables as an argument. Now, if we call our first function and pass the values of the second function it’s  going to work perfectly.


```jsx

function sum(a,b,callback){

callback(a + b)

}

function handleSum(sum){

console.log(sum)

}

sum(1,2,handleSum)

```

If we run the above code snippet it prints out the result of the sum variable which is three in our case. All of this is very confusing at the beginning, But it will come naturally when you keep practicing.

Callback functions are a common use-case in JavaScript that has a feature called anonymous functions. Anonymous functions are functions without giving them a name and writing them directly where we want to run them.

```jsx

function myName(name,callnack){

callback("Hello" + name)

}

myName("Jhon",function(variable) {

console.log(variable)

})

```

Running the above code snippet will print out the text “Hello Jhon” in the console. You will notice that this and the code before it does the same thing only this time we didn’t create two functions instead we just used an anonymous function to do the work of the second one. Anonymous functions are the same as a normal function we just write it where we want to call it instead of creating it first.