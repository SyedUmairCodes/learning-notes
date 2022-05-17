# Modules in JavaScript:
The most common topic that many people don't learn or fail to learn in JavaScript is how the module system in JavaScript works. It's not the learners fault because JavaScript has a strange history with how the language handles modules.

A big machine is made up of smaller parts connected together, these smaller parts can be considered as modules. The advantages of using individual modules are reusability,  composability, leveraging, Isolation, and organization. Even if one part of the machine broke you won't have to buy a whole new machine instead you can just buy the broken part and replace it. This process saves both time and money. This whole process can be applied to creating a software as well.

We can build different pieces of our program individually and then join them together to create a complete product.

Each module has three different parts, the first part being the dependencies. If one part of the program needs another one to work we can import it as a dependency. The second part of the module will be the code of the module and lastly the third part is the export.
Whatever we export from a module will be available to the module that imports it.

Whenever you think of modules in programming your files are like modules which work together to make your program.
> In a webpage the HTML, CSS, and JavaScript all are separated in there own files and are linked together.

## IIFE:
The IIFE pattern or immediately invoked function expression in JavaScript is a way to wrap our functions in parenthesis then invoke them. This helps filter out local variables from the global scope. 

The IIFE modules pattern is just creating different modules in your program by wrapping each file inside its own IIFE or an Immediately invoked function expression.

The first downside to using this module pattern is that we have to remember to write an IIFE for each of our files and the second is that we will still have a global namespace.
The order in which we import our scripts or files is also an important factor.

## CommonJS:
If we were to create our own module standard we want to implement a file-based structure, explicit imports and exports. If we were to use this type of module system it would remove all of the problems that we had with IIFEs 

This standard isn't just something that a few people use, in fact it is called CommonJS. 
If you are writing code in Node.js it will be very similar to you because CommonJS is baked into Node.js but there is also another problem that browsers don't support CommonJS out of the box and you can have problems with synchronous functions.

The solution for these problems of CommonJS is a module bundler, A module bundler examines all of your imports and exports from your modules and it bundles all of them into a single file that the web browser can understand called bundle.js file. The bundle.js files makes sure that each file has access to the imports it needs and nothing gets exposed to the global state. 

## ES Modules:
Since JavaScript is a living language and it's always evolving there wasn't any thing stopping the TC39 from adding their own module system into the official spec of the language.

This new module system called ES Modules was introduced with the ES6 update and is now baked into the language itself.

ES Modules support Async operations out of the box so we don't have to use a bundler. ES Modules also made importing and exporting a whole lot easier.
