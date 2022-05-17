# How data is organized
GraphQL is very strictly typed we relate our data in GraphQL as we created it. We have an entity named category (following our e-commerce example) and another one called products. Now we have to relate them together, we can relate them together using a one to many relation i.e. A single category can have many products and a product can only have a single category. So our GraphQL query will look something like this:

```
 query{
  category(id:1){
  name
  }
  products{
   image
   name
  }
 }
 /* We can also reverse this query*/

 query{
 product(id:1){
 image
 name
 }
 category{
 name
 }
 }
```

If we evolve this to include more fields or entities our query will get more and more complex. We can have one-to-many, many-to-many, or one-to-one relation with our entities.

The data structure that we are using is called a graph data structure and that is why we call our query language GraphQL.