
# GraphQL server with a database
This architecture will be the most common for using GraphQL, the setup will have a server that uses GraphQL. When the query or mutation arrives at the server, the server responds to the query or mutation and sends back the required data. Here GraphQL is only used as query language that connects the client and the server.

GraphQL is transport-layer agnostic which means you can use it anywhere with any technology.

# Integrating GraphQL into existing systems
You can convert an existing REST API to a GraphQL one which helps with legacy code and removes the burden to maintain that code which now has some flaws in it.

# Hybrid API
It is also possible to build a GraphQL API that connects to a database as well as an old or third-party REST API. When a query comes from the client, GraphQL will decide which resource to use.

# Resolvers
If GraphQL is really all that great, then how do we gain all this flexibility?

A GraphQL server implements these fields to exactly one corresponding function that's called a resolver function. Resolver functions fetch data from its field and nothing more.

The client sends a query the resolver will call all of the functions for its field that are specified in the schema. Once the queries are resolved it retrieves the data and sends it back to the client.

# Client libraries
GraphQL is mostly used by front-end developers because it eliminates most of the shortcomings that front-end developers face with REST. There are many client libraries like Apollo that will enable you to use GraphQL on the front-end of your application, these libraries provide all the tools necessary to focus on the important parts of your application rather than dealing with other things. 
