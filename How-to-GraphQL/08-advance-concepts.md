
# Fragments
Fragments help in improving the structure and reusability of your API. A fragment is a collection of fields for a specific type.  You can make fragments to represent information that is related to the address and phone number of a user.

# Parameterizing Arguments
Type definitions can also take arguments like functions. You can pass arguments to fetch data for a specific user or a record that is two years old. GraphQL also allows default values for arguments

# Named queries with Aliases
One of GraphQL's best features is that it lets you send multiple queries in a single request. But you will run into naming errors when you're sending multiple queries asking for the same fields. GraphQL allows you to name your queries by which this error can be removed from your requests.

# Advance SDL
GraphQL's Schema Definition Language or SDL also provides many advanced features which we will now discuss.

# Object & Scalar types:
In GraphQL there are two different kinds of types, Scalar, and Objects.

Scalars are concrete units of data GraphQL has five pre-defined scalar types which include strings, integers, floating points,  Boolean, and an ID type.

Object types have fields that express the properties of that type and are compostable. Examples of object types are the User or Post type.

You can also create your own custom scalar and object types like a date type for example. 

# Enumeration
Enumeration or enums for short are a feature of GraphQL that allows expressing the semantics of a type that has a fixed set of values. We could thus define a type called Weekday to represent all the days of a week.

# Interface
Interfaces can be used in GraphQL to abstract types. It allows you to specify a set of fields that any concrete type, which implements this interface, needs to have. In many GraphQL schemas, every type is required to have an id field. Using interfaces, this requirement can be expressed by defining an interface with this field and then making sure that all custom types implement it.

# Union types
Union types can be used to express that a type should be either of a collection of other types. 

This brings up a different problem, In a GraphQL query where we ask to retrieve information about a child but only have a person type to work with, how do we know whether we can actually access this field? The answer to this is called conditional fragments.
