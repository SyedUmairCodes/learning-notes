# Arrow functions:
Arrow functions were a major part of ES6, arrow functions have two main benefits over regular functions. The first one being that they have a shorter syntax as oppose to the regular functions created with the function keyword. The second word being how arrow functions handle the **This** keyword in JavaScript.

Arrow functions have different syntax then normal functions in JavaScript, this is one of the reasons that many beginners find them difficult at first.

```jsx
 // A normal function in JavaScript
 function func(x,y){
  return x + y;
 }
// An arrow function in JavaScript
 const func = (x,y) => {
  return x + y;
 }
```

In the above code snippet, we can see the difference between the syntax of both functions. In JavaScript functions are just variables and in the case of arrow functions that's exactly what we are doing.

Arrow functions also help when working with arrays because you don't have to write the whole function keyword we can just simply create an anonymous function and perform the required functions on our array. 
