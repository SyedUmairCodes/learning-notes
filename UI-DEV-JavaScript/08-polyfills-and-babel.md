# JavaScript is Alive:
JavaScript is a living language and it's always improving or adding new functionality. As a JavaScript developer you are always going to learn about new specs or tools that will make your life easier as developer.

The biggest downside to this is that new features are added every year whenever a new version of ECMAScript is launched it needs to go through a  5-step process which we learned in [[01.ECMA, TC39, and The standardization process]]. Also the web browsers cannot compete with this speed so even the latest web browsers require at least 6 months or a year to add support for these new features. This process creates a delay for every modern web browser to add support for the new features.

# Compiling using Babel:
If you want to use these new features of JavaScript on a web browser that doesn't support them yet you can wait for your browser of choice to add these features or You can use a tool like Babel to compile your new code in a way that older browsers can understand.  

If you choose the second option you will realize that a compiler tool like babel will always be needed to run modern JavaScript in older browsers. Babel is a great way to use modern ES6 code for older web browsers that are not being updated but are still in use by many users like Internet Explorer.

# Polyfilling:
Although Babel is a great tool for compiling ES6 code to ES5 syntax so that older browsers can understand but compiling only gets our code half-way through the process. There are certain steps that we need to take if we want our modern code to be fully understandable by older browsers and that is Polyfilling.

When Babel compiles your code and changes the ES6 syntax to ES5 so that older browsers can understand what's happening but it doesn't add any new objects or methods that you might need to transform your modern code into ES5. Polyfil essentially adds new functionality to the old web browser.

Arrow functions can be compiled by Babel into ES5 syntax which means old way of writing functions using the function keyword. This is the same for classes. 
The promises feature introduced in ES6 needs to be polyfilled because Babel cannot transform the syntax of a promise to native code.