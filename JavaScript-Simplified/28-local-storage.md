# Local storage

Local storage is the storage that exists in your web browser and is only accesible in the browser. If you save a file in the chrome browser on your desktop you won't be able to access it from firefox or even the chrome browser in your phone. The data stored in local storage is only accessible from the browser it is stored in.

Local storage should only be used for storing temporary data and not important files because it can easily be cleaned and the user can also change browsers. There are three different types of browsers storage options for storing data in the browser these are, cookies, local storage, and session storage.

Each type of browser storage is different and has diffrent properties. The following table is a great way to learn the differences between them.

| Properties         | Cookies           | Local storage | Session storage                |
| ------------------ | ----------------- | ------------- | ------------------------------ |
| **Storage**        | 4KB               | 10MB          | 5MB                            |
| **Storage expiry** | Manual expiration | Never expires | Expires when the tab is closed |
| **Availablility**  | Client/Server     | Client only   | Client only                    |

Local storage works like objects you store data in a key-value pair. The default expiration value is`expire on tab` close for both cookies and local storage and you'll need to add expiry value for cookies.


**Tags:** #JavaScript 

## Previous lesson
- [[26-async-and-await]]
- [[27-fetch-api]]