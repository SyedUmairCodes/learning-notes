# Under fetching
The last lesson we discussed about [[03.Under fetching]] and we made some improvements to the e-commerce website and it now has various categories of items that they sell. Each category displays only the products that belong to that category.

If we use a REST API endpoint, our API that goes to the server would look something like this:

```
 myapi/category/1
```

If we look at what object the server returns when we ask it for the category it looks like this:

```
 {
  "id":1,
  "category":"Accessories",
  .....
 }
```

Looking at the object we can see it provides us the id and the name of the particular category which is a part of the information we need to display to the client but we also need to display all the products that belong to this category. This is a case of under fetching.

To get all of our required data we might have to make another call to another API endpoint to get all of the products that belong to this category. This endpoint only gives us the products details but not the category details and we have to make two separate requests to the server to display all of the required information to the client.

```
 myapi/products/category/1
```

GraphQL provides the right solution to this problem, using GraphQL we can create a single  query that will return us all of the required information from the server.

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

```

This GraphQL is a perfect query for our use case. Using this query we are not over or under fetching, we are getting the exact data that we needed.
