# Type Coercion:
Type coercion means changing a data type into another, such as converting an integer into a string. JavaScript has many data types that we discussed before. JavaScript provides many built-in functions to convert data types.

```jsx

let a = "123"

console.log(parseInt(a))

```

The above code snippet shows how you can parse the value of the variable which is a string to an integer by using the built-in parseInt method in JavaScript, this is called explicit type coercion. Because we are explicitly saying to convert the variable’s data type from string to an integer.

```jsx

let a = "1.3"

console.log(parseInt(a))

console.log(parseFloat(a))

```

Now, in the above code snippet even though we technically have a string value but the result in the console will be 1 because of the decimal floating-point, and the parseInt method will round off the value of 1.3 to 1 and will print out 1 in the console. In the second line, if we use parseFloat, it will return 1.3 in the console because we are now telling it to parse the value as a floating-point.

If we have an Integer and we want to convert it to a string we use a built-in function called toString() which converts our integer values to string.

```jsx

let a = 1234

conssole.log(typeof a.toSting())

```

The above code snippet will return the data type of the variable as a string because we are using the toString function and converting the integer value to a string.

Implicit type coercion is when you don’t tell JavaScript to convert a data type to another and it does it on its own. We take two variables one is an integer and another is a string and if we add these two variables together and log it into our console it will return both values together.

```jsx

let a = 1

let b = "Hello"

console.log(a + b)

```

The above code snippet will return “Hello1” printed in the console. because that’s how JavaScript works. It's very confusing at the beginning but you will understand it after practicing. When working with JavaScript, you should always re-check your data types so that you don’t run into unwanted errors.

If you are comparing variables that have different data types always use the triple equals sign “ === ” because this will not let JavaScript do type coercion just don’t do this when comparing undefined and null values.

You can also apply all of these rules to not equal as well “ ≠ ”
