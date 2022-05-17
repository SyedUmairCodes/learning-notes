# What is MongoDB
MongoDB is a database technology, and the company that makes this technology is also called MongoDB. The word Mongo comes from "Humongous" that is because this database technology is built to store huge amounts of data.

But, we already have a lot of database solutions, what makes MongoDB unique? MongoDB is also a database server that allows you to run different databases on that server.

Database solutions like MySQL use tables and columns to store data. In MongoDB your database has collections that are same as tables and inside the collections we have documents that are same as columns. Documents in MongoDB are kind of like objects in JavaScript.

MongoDB gives you the facility of schema-less flexibility. A traditional database solution like MySQL needs a schema to store and retrieve data, each field that is defined in the schema must contain a value or declared to be null. This is not the case with mongoDB, you can scale your database anyway that you like.

Documents in MongoDB store data in JSON format which is very easy to work with for developers.

### Key Characteristics
MongoDB is called a No-SQL database solution because it follows the opposite rules that SQL based database solutions like MySQL or MSSQL follow. Instead of normalizing data by storing it in multiple tables and joining them together using relations MongoDB stores data together in a single document and also doesn't force the user to follow a schema. 

This means that a collection containing user information can accept documents that have missing or undefined fields which is not possible in a SQL based database.

You can use MongoDB for an app whose database requirements have not yet been defined and it will be defined as the app scales. You also have less relations to work with because all of the data is a document.
