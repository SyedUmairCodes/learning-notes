# Comparing Variables:
We can use the double equals, greater than, and less than operators in JavaScript to compare the values of two variables with each other.

```jsx

let a = 1

let b = 2

console.log(a == b) //This will print out false

//because both values are not equal to each other.

```

We use the double equals sign to compare these two variables because a single equals sign means that A is equal to B and will swap the value of A with B and will not compare it.
We use the exclamation and equals sign to say that the two values should not be equal to each other.

```jsx

let a = 1

let b = 2

console.log( a != b) //This will return true because

//both values are not equal to each other.

```

The less than and greater than symbols are also used for comparing values. respectively

```jsx

let a = 1

let b = 2

console.log( a > b) //This will print false because a is less than b
let a = 1

let b = 2

console.log( a < b) //This will print true because a is less than b

```

We can also combine comparison operators if we want to check if a value is less/greater than or equals to a certain value.

```jsx

let a = 1

let b = 2

console.log( a >= b)

let a = 3

let b = 4

console.log( a <= b)

```

These operators are also used for comparing strings, null, undefined, and Booleans (you cannot check greater or less than values for Booleans) similarly to numbers.