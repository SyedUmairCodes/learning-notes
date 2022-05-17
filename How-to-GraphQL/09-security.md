# Security
GraphQL allows clients to create very complex queries, so the server must also be able to handle them properly. These queries could be malicious attacks on the server to take it down or still its data. There are a few ways that we can protect our servers from these types of attacks.

## Timeout
The first way to prevent hackers from stealing data from your GraphQL server is by setting up a time limit to how long a query takes to resolve. If it takes more than the allowed time it will be rejected by the server.

### Pros
- Simple to implement
- Used mostly as a last line of defense

### Cons
- Sometimes randomly cutting connections may lead to unstable behavior
- Damage could already happen within the allowed time

## Query Depth
Clients can create very complex queries and use them to launch attacks on our servers. We can limit the depth of our queries so that they return only the required data and nothing more. The schema that we define for our servers can help remove this complication.

### Pros:
- Using this approach we can sometimes cancel queries which removes load from the server.

### Cons:
- Depth alone is not enough for large-scale attacks you need to implement multiple security measures to protect your servers.

## Complexity
The depth of a query does not define how complex it is. In a lot of cases, certain fields in our schema are known to be more complex to compute than others.

Query complexity allows you to define how complex fields can be and restricts them to not accessing more data. 

### Pros:
- Can be helpful in most attacks on the server
- Rejects queries before executing them

### Cons:
- Can be hard to implement
- Can be hard to estimate the default complexity
- Mutations can have side effects due to restrictions

## Throttling
All of the solutions that we have discussed are a great way to stop large-scale attacks on our servers. But what will we do if the attackers used normal queries but multiple? The answer is throttling.

Throttling may not sound that great but in most cases, you can throttle a client if it keeps making requests over and over again.

### Throttling based on server time
You can limit clients to how much time they can access the server and then have a cool down period. They can only access the server again after the cool down period is over so that it doesn't spam our server with requests.

### Throttling based on complexity
Throttling clients' access to the server-based upon the complexity of their queries is a great way to stay within the limits of the schema.

---