# Data types:
JavaScript has different types of data that a variable can hold. A variable can hold numeric, alphabetic, and floating-point numbers as a data type in JavaScript. Each data type is defined below.

## Numbers:

```jsx

let a = 1

```

The above code snippet shows a variable that has a value of one, now the variable a is the type of number because it currently has a number as its value. If you don't know what type of data a variable is holding you can use the **typeOf** keyword to check it.

```jsx

let a = 1

console.log(typeOf a)

```

The above code snippet will print out the data type of the variable in the browser console when you run the code. In JavaScript numbers are very different than other programming languages such as C# or Python. In JavaScript whole numbers or numbers with a floating-point are called numbers while in other languages they are denoted by the **Integer and Float** data type respectively.

```jsx

let a = 123 //This is a number in JS

let b = 1.3445 //This is also a number in JS

```

We can also perform arithmetic calculations on numbers in JavaScript like addition, subtraction, division, and multiplication. It doesn't matter if we use a decimal or a floating-point number because JavaScript treats all of them as the **Number** data type.

```jsx

let a = 5

let b = 2

  

add = a + b //Addition

subtract = a - b //Subtraction

multipy = a * b //Multiplication

divide = a / b //Division

```

In JavaScript, the code we write is executed from top-to-bottom but mathematical or arithmetic operations will always occur as they do in real life.

## Strings:
When you want to write text in JavaScript you use the **String** data type. But JavaScript won't understand your text if you just type it out instead you will have to type your text between single or double-quotes.

```jsx

let my_name = Jhon //This is not considered as a string

let full_name = "Jhon Doe" //This will be considered as a string

```

Now, what will happen if you want to put a string inside another string? A good question. The solution is very simple you just write the first text in single quotes and then write the second text in double quotes inside the single quotes. If you write text inside single or double quotes and then also write the second text in the same quotes as the first one you will run into syntax errors.

```jsx

let wrong_greeting = "Hello, my name is "Jhon"."//This is the wrong way to write string

//inside another string

let greeting = 'Hello, my name is "Jhon".' //This is the correct way to write a string

//inside of another string

```

You can combine multiple strings that will form sentences. We use the "+" operator to add strings together.

```jsx

let first_name = "Jhon"

let second_name = "Doe"

  

let full_name = first_name + second_name //This adds the two name together

//and make it into a single name.

```

## Booleans:

**Booleans** are a data type available in programming languages that have only two values **true** and **false.** Booleans are different from strings and numbers because you cannot use a variable that is a Boolean like a string or a number for example we cannot add two Booleans together using the "**+"** symbol.

```jsx

let a = true

let b = false

let c = a + b //This is not correct and will result in errors.

```

We use special operators to perform operations on Booleans called the **AND and OR** operators denoted by the **&& and ||** symbols respectively.

```jsx

let a = true

let b = false

console.log(a && b) //This is how the AND operator is used

console.log(a || b) //This is how the OR operator is used

```

## NULL and Undefined:
Up until now, we have learned that every variable must have a data type, What if a variable didn’t have any data type assigned to it? For situations like these, we use the undefined or null data type. undefined means that we have not yet defined a data type for the variable and we can assign it a value later on.

```jsx

let a = undefined //This variable's value has not yet been defined.

```

The data type of null is assigned to a variable when we know that it won’t define a data type for it but we need it to run our program correctly.

```jsx

let a = null //This variable does not have any data type.

```

If you use the **typeOf** keyword to check out the data types of variables that have undefined or null you will get different results. For the variable having the undefined value, your result will also be undefined. But for the variable that has a null value, it will simply return the **object** as the data type because that is how JavaScript works. We don’t need to go much deeper into it.