# Objects in JavaScript:
Objects in JavaScript are core part of the language. You will at some point have to use them in your code. Creating an object is simple, you define a variable and assign it a curly braces and use the dot notation to values or functions to your object.

```jsx

 let person = {};
 person.name = "Jhon";

```

If we have an object, and we wanted to create a child object we can use the object create method.

```jsx
 const parent = {
  name = "Jhon";
  age = 22;
  heritage = "Irish";
 }

 const child = Object.create(parent)
 child.name = "Harold";
 child.age = 6;

 console.log(child) //This will return only the name and age of the child.
 console.log(child.heritage)

/*This will return Irish as the heritage becuase we used the Object.create property to create a child object from our parent Object */ 
```

## Prototype:
Prototype in JavaScript is a property of an Object that point to that its just a property on a function.

>A prototype in just a property on a function that point an Object.
