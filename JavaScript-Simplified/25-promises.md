# Promises
A promise in JavaScript is a better version of a callback function. Promises in JavaScript work just like they do in real life. A promise is a piece of code that you execute and  it succeed or you execute it and it fails and shows an error,

```jsx 
const promise = new Promise((resolve,reject) => {})
```

The above code block displays how a promise is written in JavaScript. Notice that there are two parameters in the arrow function inside the promise. Resolve, is what happens when the promise is successful and reject is what happens when the promise is unsuccessful.

```jsx 
const promise = new Promise((resolve,reject) => {
 const sum = 1 + 2

 if(sum === 2){
   resolve("Success")
  }
  else{
  reject("Fail")
  }

})

promise.then(message => {
console.log(message)
}).catch(message => {
 console.error(message)
})

```

The above code snippet is a great example of how promises work.