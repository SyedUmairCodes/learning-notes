# Forms and HTTP POST
Our example web page also contains a form-element which is used to add new notes. Below the text-box there is a save button that saves our note in the server and loads it into our browser.

When the button is clicked, the browser sends whatever is written in the text-box to the server. It only takes five HTTP requests to submit the form. 

The first one is an HTTP POST request to the server address *new_note*. The server responds with a HTTP 302 status code. This is a redirecting code. The server tells the browser that redirect user to show all the notes and the new note is displayed at the last line.

In the HTML document the form or "text-box" element has a method attribute of POST which tells the browser that you need to send this data to the server and then the server saves it in a JSON file.

**Tags:** #full-stack-open