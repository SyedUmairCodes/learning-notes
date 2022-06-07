# Loading a page containing JavaScript
- The browser fetches the HTML code defining the content and the structure of the page from the server using an HTTP GET request.
- Links in the HTML code cause the browser to also fetch the CSS style sheet _main.css_...
-  ...and a JavaScript code file _main.js_
- The browser executes the JavaScript code. The code makes an HTTP GET request to the address [https://studies.cs.helsinki.fi/exampleapp/data.json](https://studies.cs.helsinki.fi/exampleapp/data.json), which returns the notes as JSON data.
-  When the data has been fetched, the browser executes an _event handler_, which renders the notes to the page using the DOM-API.

**Tags:** #full-stack-open