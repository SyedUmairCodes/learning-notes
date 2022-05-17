# Arrays:
We have learned almost everything about variables that contain a single value. What if we want to pass a list of data to a single variable? We can do that by using Arrays, Arrays are a list of data that is assigned to a single variable.

In JavaScript, you can create an Array by using the square brackets ”[]” and separate list items using a comma.

```jsx

let array1 = ["a","b","c","d"];

let array2 = [1,2,3,4,5];

/*This is how you can define arrays in JavaScript*/

```

Arrays start from zero, so the first item in an array will be at index zero and the second one will be at one index. If we want to access the letter c in the above-defined array I will call the second index of that array and it will return the letter c because arrays start from zero.

```jsx

let array1 = ["a","b","c","d"];

console.log(array1[2]);

```

If we want to add another index to our array we use a built-in array method called **push()** which adds a new index to our array.

```jsx

let array1 = ["a","b","c","d"];

array1.push("e","f","g");

console.log(array1);

```

If you run the above code snippet you will see that the letters e,f, and g have been added to our array list. Arrays can contain multiple types of data inside them, let's say we have an array that contains information about a person.

```jsx

let myDetails = ["Jhon",22,"Software engineer"]

```

In the above code snippet, we have defined an array that contains the details of a person and it also has multiple data types. If we want to access his name we use index zero, his age is at the second index which will be 1, and finally, his job is at the last index which is the third index or number 2.

Since arrays are a list we can also put an array inside another array, like if we want to list all the names and ages of the employees of a company we can use an array list inside another array.

```jsx

let employee = [["Jhon",22],["Drake",24],["Micheal",22]];

```

This is called a nested array, if you want to access the data inside a nested array you can do that just like you did with a simple array.

```jsx

let employee = [["Jhon",22],["Drake",24],["Micheal",22]];

console.log(employee[0]);

```

The above code snippet will return all of the data which is at the index zero. In our case, it’s the data of john. if you want only the age of your employees you can specify the index of the inner array as well.

```jsx

let employee = [["Jhon",22],["Drake",24],["Micheal",22]];

console.log(employee[1][1]);

```

The above code snippet will print out the age of Drake which is 24. This is a very simple way to access specific data in a nested array.