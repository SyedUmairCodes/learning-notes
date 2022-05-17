# Advance variables:  

There are three different ways to define variables in JavaScript. We can define variables using the **var, let, and the const** keywords.

```jsx

let a = 1

var a = 1

const a = 1

```

The difference between them is that if you define a variable using the let keyword you can change its value according to your code. A variable declared using the const keyword is a constant variable and its value cannot be changed throughout the entire code.

The var keyword is the old way to define a keyword which was replaced by the let keyword when ES6 was introduced. Before ES6 was introduced the var keyword was the only way to create variables in JavaScript, The let and const keywords were introduced in ES6.

The reason the var keyword was replaced by the let keyword is that variables created using the var keyword acted very differently as compared to variables in other programming languages. When we discussed scoping and hoisting we learned that variables cannot be hoisted and that variables are only available inside their scopes. That is not the case with variables created using the var keyword. Variables created using the var keyword can be accessed outside of their scopes, meaning you can hoist the variables created using this keyword, You can also redefine variables created with this keyword and it will just overwrite the previous one.

The var keyword goes against all rules of modern JavaScript and is there not recommended, you can use the let and const keywords instead of var.