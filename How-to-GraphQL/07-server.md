# Server:
GraphQL is mostly known as a front-end-focused API technology because it helps clients access data in a better way than REST. But the API is implemented on the server-side. GraphQL provides a better development experience because it handles all the things required for the queries and mutations so that the developers can focus on the more important things.

## Execution:
GraphQL provides an execution algorithm along with a schema and query language. The algorithm is pretty simple, queries are traversed field by field by executing resolvers for each field.

GraphQL server provides default providers so that you don't have to provide resolvers for every single field.

## Batched resolving:
If you have a resolver that fetches data from a database, it might e called multiple times during query execution. We can wrap our queries in a fetch function to remove this problem. The fetch function will wait for all of the resolvers to run, then make sure to only fetch each item once. If your API supports batched requests we can also make only fetch requests for multiple requests of the same type.
