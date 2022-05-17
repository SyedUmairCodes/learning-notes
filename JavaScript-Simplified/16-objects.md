# Objects:
We will now learn about Object types in JavaScript, Objects are the most important part of learning JavaScript. An Object is a collection of data which is related together in some way.

Let's say, that we have information about our employees and we want to print it out. We can use variables for each part of the employees info, we can use a nested array, or we can create an object that contains all the information about the employee.

`````` jsx
 let name = "John";
 let age = 22;

 //Instead of using variables we can use a object.

 let employee = {name:"John",age:22};
 console.log(employee);
``````

In the above code snippet you can see that the variable employee is actually a object, objects use something known as key-value pairs to store data in them. The property name is a key and the string john is the value of that key, this is same for the age as well.
We can also select individual properties from the object like we did arrays.

``````jsx
 let employee = {name:"John",age:22};
 console.log(employee.name);

``````

We can easily access all of the properties of an object by using a period and then selecting which individual property that we want to display instead of the full object. 

Even the **console.log** function that we have been using to print or variables is an object which has a log function as a property.

```jsx
 console.log(console); 
```

The above code snippet will print out all of the functions that the console object contains. 

How can we add functions to an object? The answer is just like we added our variables, because in JavaScript a function is just a variable.

```jsx
 let employee = {name:"John",age:22, calculateSalary: function(){
   hoursWorked * 2.5;
 }};

 console.log(employee.calculateSalary);

```

In the above code snippet we have passed a function to an object, and when we use console.log to print it out it will print out the employees salary when the hoursWorked variables is provided.

Objects work the same way as arrays do, so you can say that they are a collection of information.

