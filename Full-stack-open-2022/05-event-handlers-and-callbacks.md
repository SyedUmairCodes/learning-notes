# Event handlers and Callback functions
This code is a bit of odd-looking:
```js
var xhttp = new XMLHttpRequest()

xhttp.onreadystatechange = function() {
  // code that takes care of the server response
}

xhttp.open('GET', '/data.json', true)
xhttp.send()
```

The request to the server is sent on the last line, but the code to handle the response can be found further up. What's going on?

```js
xhttp.onreadystatechange = function () {
```

On this line, an _event handler_ for event _onreadystatechange_ is defined for the _xhttp_ object doing the request. When the state of the object changes, the browser calls the event handler function. The function code checks that the [readyState](https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest/readyState) equals 4 (which depicts the situation _The operation is complete_) and that the HTTP status code of the response is 200.

```js
xhttp.onreadystatechange = function() {
  if (this.readyState == 4 && this.status == 200) {
    // code that takes care of the server response
  }
}
```

The mechanism of invoking event handlers is very common in JavaScript. Event handler functions are called [callback](https://developer.mozilla.org/en-US/docs/Glossary/Callback_function) functions. The application code does not invoke the functions itself, but the runtime environment - the browser, invokes the function at an appropriate time, when the _event_ has occurred.

**Tags:** #full-stack-open