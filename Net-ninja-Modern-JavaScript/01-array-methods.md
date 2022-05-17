# Array Methods

## Filter Method
The filter array method filters out the required result from an array. This method takes a callback function as an arrgument.

```js
const scores = [10,20,24,27,30,35,40,45,50];

const filteredScores = scores.filter((score) => {
 return score > 20
})
 console.log(filteredScores);

```

The above code snippet displays how the filter method works and it will display all the scores that are greater than 20 in the console. 

## Map Method
The map method takes an array and iterates over it and then creates a new updated array.

```js
const prices = [20,24,27,30,35,40,45,50];

const salePrices = prices.map((price) => {
 return price / 2;
});
 console.log(salePrices);
 
 ```

## Reduce Method
The reduce method works differently from the filter and map methods because it doesn't return a modified array or a new array. It returns a single value only. (The value can also be an array.) 

```js
const scores = [20,24,27,30,35,40,45,50];

const highScores = scores.reduce((acc, curr) => {
 if(curr > 20){
   acc++;
 }
 return acc;
},0);
 console.log(highScores);
 
 ```

The above code snippet shows an example of the reduce array method.

## Find Method
The find method is a new function that was introduced in JavaScript and it helps to find a certain value in an array.

```js

const scores = [20,24,27,30,35,40,45,50];

const highScore = scores.find((score) => {
  return score > 20;
})

console.log(highScore)


```

This method will only display the first value of the array that passes the condition defined in the callback function of the method.

## Sort Method
The sort method helps to sort values in an array according to the given criteria. You can sort the names of employees in an array.

```js
 const names = ["Mario","Ryu","Peter","Tony","Scarlet"];

 names.sort();
 console.log(names);

```

Methods can also be used together for more complex results. This is called method chaining.