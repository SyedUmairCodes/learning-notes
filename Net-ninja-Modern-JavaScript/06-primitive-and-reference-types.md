# Primitive and Reference types
Primitive types in JavaScript are all of the data types that we normally use except for objects.

Objects, functions, and array are all reference types.

When we create a primitive value like a string, that value is stored in memory in an area called the stack. Values stored in the stack can be accessed quickly but the space in the stack is very small and limited.

Reference types, on the other hand are stored in a place called the heap.

A variable can be assigned an object. So, in the background what JavaScript does is that it adds that variable to the stack and then creates a pointer that points to the object that is placed in the heap.
