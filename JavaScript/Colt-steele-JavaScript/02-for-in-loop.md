# For-in loop
The for-in loop is used to iterate over the properties or keys in an object.

The main difference between the for-of and the for-in loop is that the for-of loop iterates over the actual value of the array or object that it's being iterated over and the for-in loop only iterates over the keys of the array or object.

```js
  const users = {
   bob : 22,
   sally: 25,
   jake: 33
  }
  
 for(let user in users){
   console.log(user);
   console.log(users[user]);
 }
```

**Tags:** #JavaScript 

## Next lesson
- [[03-prototypes]]