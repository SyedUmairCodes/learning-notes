# NaN: Not a Number:
Not a number or NaN for short is a side effect of type coercion. If you run the below code snippet it will return NaN in your console because a string is not a number.

```jsx

let a = "Hello world"

console.log(parseInt(a))

```

NaN is very unique because if we want to compare the above variable with NaN itself it will return false, which is kind of weird since the variable is technically NaN.

```jsx

let a = "Hello world"

console.log(parseInt(a) == NaN) //This will return false.

```

This is how just JavaScript is built it has its quirks, there is a special way to check if a variable is NaN in JavaScript which is a built-in function of JavaScript called **isNaN().** If we pass in our variable in this built-in function it will be true, This concept in JavaScript is very confusing and straightforward at the time.

```jsx

let a = "Hello world"

console.log(isNaN(a)) //This will return true.

```
