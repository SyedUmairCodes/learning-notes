# Fetch API

The  fetch API in JavaScript allows you to query data from in the internet from different websites that allow you to query data via a public API.

There are many free and public APIs available to us that we can use. These APIs give us the data in the form a JSON array and we use  them we can use built-in methods that JavaScript provides us to show that data normally.

```js
const api = "<Website URL>";

fetch(api).then(response => {
  return response.json()
}).then(data => {
    console.log(data.map(user => user.name))
})
```

If the internet disconnects or there is a server failure and your app cannot connect to the API and for that you can set up try-catch blocks to show an error page in your application.

You can also send data using the fetch API from your application to the server. You'll just need to define the `POST` method in the function which you're using to send data.

```js
const api = "<Website URL>";

async function sendData(){
    const response = await fetch(api,{
    method: "POST",
    headers:{
    "Content-type":"application/json"
},
   body: JSON.stringify({
        title: "New post"
})
})
const post = await response.json()
console.log(post)
}

sendData();
```