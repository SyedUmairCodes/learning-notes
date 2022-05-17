# Tooling and Eco-system
The ecosystem of GraphQL is rapidly growing because GraphQL makes it easy for developers to create complex solutions easily. The client and server both can access the schema which is known as introspection.

## Introspection
The designers of the schema already know what the schema looks like but how can clients discover what is accessible through a GraphQL API? We can ask GraphQL for this information by querying the __schema meta-field, which is always available on the root type of a Query per the spec.

Introspection is a really powerful tool that dives deep into more details about fields and types available in the introspection schema.

## GraphQL Playground
GraphQL Playground is a powerful “GraphQL IDE” for interactively working with a GraphQL API. It features an editor for GraphQL queries, mutations, and subscriptions, equipped with autocompletion and validation as well as a documentation explorer to quickly visualize the structure of a schema (powered by introspection). It also can display your query history or lets you work with multiple GraphQL APIs side-by-side. It also seamlessly integrates with graphql-config.

It is an incredibly powerful tool for development. It allows you to debug and try queries on a GraphQL server without having to write plain GraphQL queries over curl, for example.

