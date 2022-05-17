# Array methods:
Array methods are pre-defined functions that are available for arrays that make manipulating arrays much easier.

## For each
The most common array method is the **forEach** method. What this method does is that it takes a function and that function is run for each element that is present in the array.

```jsx

 const array = [1,2,3,4,5];

 array.forEach(number => {
  console.log(number);
 } );

 /*This will print all of the elements in the array.*/

```

The **forEach** method can also take another argument called the index, Index is the place in which the current element is placed in the array.

```jsx

 const array = [1,2,3,4,5];

 array.forEach(number,index => {
  console.log(number + "" + index);
 } );

 /*This will print all of the elements and their index in the array.*/

```

## Map
The map array method is very similar to forEach, both of them loop through each element in the array the only difference is that map always returns something from our function call. The map function doesn't return our array, it creates a new array and returns the new one to us.

```jsx

 const array = [1,2,3,4,5];

 array.map(number => {
  return number;
 } );

 const newArray = array.map(number => {
  return number * 2;
 })

```

## Filter
The filter function, like the name suggests filters out selected elements from the array. This method like map does not modify our defined array but creates a new one with only the selected values.

```jsx

 const array = [1,2,3,4,5];

 const newArray = array.filter(number => {
  return number > 2;
 } );

 /*This will print all of the elements that are greater than 2 in the array.*/

```

## Find
Find is like the filter method but a little different, filter returns all of the elements in the array but find only returns the first element it finds that matches the criteria being passed.

```jsx

 const array = [1,2,3,4,5];

 const newArray = array.find(number => {
  return number > 2;
 } );

 /*This will print only the first element that is greater than 2 in the array.*/

```

## Sum
The sum function is not that much used unlike the previous methods but its still useful in many scenarios. The sum function will return true or false depending on the criteria being passed to it, it won't return a new array or modify our existing one.

```jsx

 const array = [1,2,3,4,5];

 const newArray = array.sum(number => {
  return number > 2;
 } );

 /*This will print true or false if there are elements greater than 2 in the array.*/

```

## Every
The every method is the inverse of the some method, it will check each element of the array and will return true or false depending on the criteria provided.

```jsx

 const array = [1,2,3,4,5];

 const newArray = array.every(number => {
  return number > 2;
 } );

 /*This will print true or false if all of the elements greate than 2 in the array.*/

```

## Reduce
The reduce method simply reduces the array to a single value. This method requires at least two parameters, the previous element and the element that you need to find.

```jsx

 const array = [1,2,3,4,5];

 const newArray = array.reduce((sum,number) => {
  return sum + number;
 },0 );


```

## Includes
The easiest array method is called includes. You pass it a value and it return the true or false if that value exists in the array.

```jsx
 const array = [1,2,3,4,5];

 const includes = array.includes(2);
 console.log(includes);

```
