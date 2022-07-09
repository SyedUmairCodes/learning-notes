# Global Vs. Window object
Node provides us the global object which is the equivalent of the window object in JavaScript. It also provides us many alternatives to popular JavaScript methods that are browser specific.

The document method is replaced by process, history by module, location by filename, and navigator by the require method. There are many more methods that are alternatives to the ones that JavaScript uses because they are used by the window object which is used to manipulate the dom in the web browser. Node works outside of a web browser so we need alternatives to these dom methods.

#node 