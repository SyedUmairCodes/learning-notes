# Clients
Using the GraphQL API in the front-end is a great way to develop and implement new functionality for the client. Some features are necessary for almost every application.

- Queries and mutations without constructing HTTP requests
- Integrate a View-layer
- Caching
- Query validation according to the schema

 You can still use the normal way of using HTTP requests to fetch data but it's a hassle that GraphQL can easily take care of so that you can focus on the more important parts of your application.

## Directly sending Queries and Mutations
GraphQL allows you to fetch and store data in a declarative way removing the hassle of low-level networking tasks.

## Integrating View-layer
The client receives the data from the server which is being handled by the GraphQL client and it will automatically update the data on the front-end without any work. This will be different for every framework out there.

## Caching
Caching means storing some data locally on the client for a better user experience. This also saves bandwidth and halves the server's load. For a better experience, you should first normalize the data. 

## Schema validation
The schema contains all information about the data that a client can request from the server using a GraphQL API. Using this method, you can validate and optimize your queries during build time

## Co-locating views and Data dependencies
GraphQL allows tight coupling of views and data, this greatly improves the development experience. Both of the requirements are shown side-by-side. However, this experience is not always the same for every technology.