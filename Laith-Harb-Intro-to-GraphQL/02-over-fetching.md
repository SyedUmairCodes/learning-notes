# Over fetching
GraphQL prevents over fetching of data because the queries passed through GraphQL will only return the data that was defined in the query no more than that no less than that.

## A real life use-case
You are running an e-commerce store, you are displaying all the items available and when someone clicks on a particular product they are directed to the that products page.

We have our client (computer/mobile) and we have our server. The server is in-charge of communicating with the database and returning that data to the client. What we have currently done is that when we click on the particular item the client asks the server to get all the data about that exact product from the database and show it to the user.

This is done via an API endpoint which goes to the server from the client. A typical endpoint will look like this:

```GraphQL
 myapi/products/1
```

This API tells the server to return the data about the product that has the id of one. The server responds to the clients requests and sends back all of the required information to the client in the form of an object. 

```GraphQL
{
 "name":"Product 1",
 "description":"Product description",
 "price":55,
 "image":"image-1",
 "created-at":2021-10-1,
 "rating":4.5
}
```

If we talk about our products page the server doesn't return a single object because the products page has a lot of data about multiple products so it will return an array containing  the information about all the products.

```GraphQL

 {
 "name":"Product 1",
 "description":"Product description",
 "price":55,
 "image":"image-1",
 "created-at":2021-10-1,
 "rating":4.5
}

{
 "name":"Product 2",
 "description":"Product description",
 "price":55,
 "image":"image-",
 "created-at":2021-10-1,
 "rating":4.4
}

{
 "name":"Product 3",
 "description":"Product description",
 "price":50,
 "image":"image-3",
 "created-at":2021-10-1,
 "rating":4.1
}

```

In the single product page we can use all of the data available to us about a product to the customer. That is not the best option for all the products page. We only need the name and the image of the product to show it on the products page.

The client is over fetching data in the case of the products page. We only need the name and the image and not every thing about the product.

The solution to this over fetching problem is using GraphQL. With GraphQL instead of hitting a particular endpoint and over fetching our data we can structure our queries to return exactly what we want it to return. Our products page query will look something like this.

``` GraphQL
 query{
  products{
   image
   name
  }
 }
```

This exact over fetching scenario can also happen in our single product page. The query for the single product will look something like this. Instead of querying for all products we are now selecting a single product and passing the product id as an argument. 

```GraphQL
 query{
  product(id:1){
  image
  name
  description
  price
  }
 }

```

If we look at REST and GraphQL we can notice that a REST API provides all of the information that is available at the endpoint that we requested but with GraphQL we can filter the data according to our needs.