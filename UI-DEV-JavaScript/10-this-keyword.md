# THIS Keyword:
In order to understand the **This** keyword in JavaScript we first need to understand why we even have a **This** keyword in JavaScript in the first place.

The **This** keyword allows us to reuse functions with different context. Or you can say that it allows us to decide which object should be focal when we are invoking a function or method.

There are four rules of the **This** keyword which are implicit binding, explicit binding, new binding, and the window binding.

## Implicit binding:
Implicit binding is the most common rule when you are trying to figure out what exactly does the **This** keyword do.

We are going to create an object.

```jsx
 var me = {
 name = "Jhon";
 age = 22;
 sayName = function(){
  console.log(this.name);
 }
 };

 me.sayName()
```

In the above code snippet we create an object with two values and a function and we are using the **This** keyword to log the name property of the object, we the invoke the function by calling the say name function.

In the case of implicit binding, when the function is invoked the **This** keyword will look to the left of the dot and that is what it is going to reference.

## Explicit binding:
If we have a function outside of our object but in the global scope and we want to call it from the object?

```jsx
 
 sayName = function(){
  console.log(this.name);
 }

 var me = {
 name = "Jhon";
 age = 22;
 };

 me.sayName()
```

Every function in JavaScript has a call property that we can use the function that is outside the object. The call property requires a context for that we will pass the me function. The **This** keyword in our function is going to represent the object. This is an example of explicit binding using the **This** keyword.

```jsx
 
 sayName = function(){
  console.log(this.name);
 }

 var me = {
 name = "Jhon";
 age = 22;
 };

 sayName.call(me)
```

## New binding:
We have a function that takes three arguments, when we invoke this function, since we are using the **This** keyword in our function JavaScript will create a new object in our function.
```jsx
  var animal = function(color,name,type){
   this.color = color;
   this.name = name;
   this.type = type;
  }

  var Zebra = new Animal('Black and White','Marty','Zebra');
  
```

The new binding rule states that whenever the function is invoked with the new keyword, The **This** keyword in that function is bound to the new object that is being constructed.

---
## Window binding:
We have a function that only logs a value to the console.

```jsx

var Age = function(){
  console.log(this.age);
};

var me = {
 age:22;
}

Age();

```

Looking at the above code snippet if we use explicit binding and invoke the function using the call property. But we are just invoking the function without telling anything to it. You will get undefined printed out on the console.

This happens because if we don't provide any context to the **This** keyword it default to the window object. If we set the age property on the window it will then print out the age on the console.
```jsx
window.age = 22;
Age()
```
