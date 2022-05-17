# GraphQL is the Better REST:
REST is the standard for designing web-APIs as it offers great tools such as stateless servers and a structured way to access resources. But as the client requirements keep changing rapidly REST just can't keep up because of its inflexibility.

GraphQL was invented to keep up with the demand for a flexible and efficient way to access resources from a variety of clients, and it does the job it was created to do, that is to remove the shortcomings of REST.

To see the major things that differentiate REST and GraphQL when it comes to APIs we will look at the following points.

## Data fetching
A REST API typically provides the data via multiple endpoints. Using  GraphQL you'll only have to use a single endpoint from the GraphQL server which contains the specific data, which is returned as a JSON result.

## Over and under fetching

REST provides a structured/fixed way to access data which sometimes results in over and under fetching of data. It can be a very hard task to design an API that provides the user with the exact data they want if you're using a REST API. 

### Over-fetching
Over-fetching happens when a client downloads more data than it needs from the server, this *excess* data is basically useless to the client and also wastes bandwidth if the client is a mobile or a tablet device.

### Under-fetching
Under-fetching happens when the client needs more data than the server provided so it makes more than one request by hitting multiple endpoints. This also wastes bandwidth on mobile and tablet devices.

## Rapid iterations
REST APIs are made that each endpoint provides the data that a view needs in the client-side application. This is helpful as it will only provide the required data that the client needs.

This approach will backfire if you're going to make changes on your front-end because there will be a high risk of under-fetching or over-fetching the data from the server using the REST API. This slows down development at a great margin.

GraphQL solves this problem thanks to the flexible nature of GraphQL, rapid changes on the front-end are no problem for a GraphQL API as it will only provide the data the clients want so that the development team can make changes to the query whenever they desire.

# Insightful analytics
GraphQL provides a fine-grained insight about data being requested by the client from the server. As specific data is being called by each client, it can be easy to determine what data is most important for the user.

It's also possible to do a low-level performance monitoring of the API using the resolver functions that GraphQL provides, these sometimes contain crucial information that can greatly improve our API.

## Schema and Type system

GraphQL uses a strongly typed system to define an API. The types that are exposed in an API are written using a schema using the GraphQL Schema Definition Language(SDL). This schema acts as a contract between the server and the client to define how a client can access data from the server.

After the schema is defined the back-end team can further continue their work and the front-end team can refine the front-end as they require.
