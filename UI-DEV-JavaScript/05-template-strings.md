# Template literals:
Template literals are a new feature introduced in ES6. Some developers prefer to call them template strings but its the same thing whichever way you call it. Template literals are excellent for string interpretation and multi-line strings.

Template literals help you to add string inside another string. Or if you want to put a quote inside a text because a quote starts and ends with double-quotations you can use template literals to add that in your string. Another use case for template literals is that you can add variables inside your strings.

```jsx
 let name  = "John";
 let age = 22
  
 let person = `My name is ${name} and I am ${age} years old.`
```

The above code snippet will print out the phrase "My name is john and I am 22 years old." This provides a great opportunity to make things dynamic because you can just change the values of the variables and the text will be auto updated. This is mostly used when you want to show how many downloads your app got or how many people are using your service. 

Keep in mind that template literals start with a backtick and not with a double quote.
