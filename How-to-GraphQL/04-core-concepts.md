
# Schema Definition Language
GraphQL uses its own type system that defines the schema of an API. The syntax for writing the schema is called Schema Definition language.

# Queries
In REST APIs, data is loaded from specific endpoints. Every single endpoint contains a defined structure of the information that it returns, meaning that data requirements of the client are encoded in the URL that it hits.

GraphQL uses a completely different way, instead of having multiple endpoints that provide structured data, GraphQL only exposes a single endpoint because the returned data does not have a fixed structure.   

# Queries with arguments
GraphQL queries can also have arguments if you define that in the schema. Like returning only the users that used the application from a mobile device. 

# Mutations
GraphQL uses queries to retrieve data from the server. Mutations in GraphQL are used to send data from the client to the server. Mutations are the same as CRUD operations in REST. They also have the same structure and can also have arguments like queries.

Mutations have unique ID types that are generated from the server.

# Subscriptions
Modern client applications in today's time may require a real-time connection to the server to get immediate information from the server. GraphQL uses subscriptions for these types of use-cases.

Whenever a client subscribes to an event, it will initiate and hold a study connection to the server. When the subscribed event happens the server immediately sends the new data to the client. Mutations follow a request-response cycle. They are written in the same syntax as queries and represent a stream of data sent to the client.

# Schema
The schema is one of the most important factors in a GraphQL API. The schema defines the capabilities of the API and defines how the client can access the data from the server, kind of like a contract between the client and the server.
