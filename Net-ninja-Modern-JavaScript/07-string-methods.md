# Strings
If you want to write text in JavaScript you will need to use the String data type. Strings can contain any characters or text including variables in them.

## String Methods
There are many pre-defined methods that you can use on strings to make your code easier and more efficient.

### Index Of
The IndexOf method tells you the exact index of a character in a string.

```jsx
 let greeting = "Hello World!";

 let index = greeting.indexOf("w");
 console.log(index);
```

### Slice 
The method allows you to slice your string between the length that you define.

```jsx
 let greeting = "Hello World!";

 let slice = greeting.slice(2,5);
 console.log(slice);
 ```

### Sub string
The sub string method like the name suggests creates a new sub string from your previous string that you provided.

``` jsx
 let greeting = "Hello World!";

 let substring = greeting.substr(0,5);
 console.log(substring);
```

### Replace
The replace method again as the name implies replaces a single or multiple characters from your previous string. It takes two arguments like the splice and substr methods. The first one is which you want to replace and the second is the one which is going to take the place of the replaced character.

```jsx
 let greeting = "Hello World!";

 let replace = greeting.replace("w","Y");
 console.log(replace);
```
