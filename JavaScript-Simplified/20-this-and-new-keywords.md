# This and New key word
In JavaScript you can create objects by using the value-pair method or you can use the THIS or NEW keywords

```jsx

function createUser(name,age){
 return {name:name,age:age}
}

const user = createUser("Jhon",22)
console.log(user);

```

The above code snippet is the easiest and most simplest way to create an object in JavaScript.

If you use the date function to print the current date and time you will create a date object using the new keyword.

```jsx
const date = new Date()
console.log(date);
```

Now, the date variable is also an object because it contains its own methods which you can see using the dot notation. When you use the NEW keyword to create an object the right side of the NEW keyword is called a constructor. 