# Scoping:
If we have a function that prints out a string we can write the function and call it in our code easily,

```jsx

function myName(name){

console.log("Hello" + name)

}

myName("John")

```

The above code snippet will print out the text “Hello John” because we passed john as the argument that our function requires.

Now, if we have a variable called name and we give it the property of “John” and then pass the variable in the function it would also work that way. But there are now two variables of the name called “name”. The first one is the functions parentheses and the second one we created. The question is if there are more than two variables of the same name why aren’t we getting any errors.

```jsx

function myName(name){

console.log("Hello" + name)

}

let name = "John"
myName(name)

```

This is all thanks to a feature called scope or scoping in JavaScript. The way that scoping works is every time that you have a set of curly braces like the inside of function will have its scope. Every function has its scope. We also have the global scope in JavaScript which contains all of the code that you have written in the JavaScript file. inside the global scope, we have smaller scopes as we mentioned before.

Scopes are like one-way doors if you are in the scope of a function you can access the global scope. But you cannot access the scope of a function from the global scope.