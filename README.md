# basic concept

## terms

### Resolvers

## techniques

### Changesets

### Dataloader

a cache feature for the same request concurrently.

[original repo](https://github.com/graphql/dataloader)
[Go version](https://github.com/vektah/dataloaden)

### Field Collection

you can query for a collection of **fields** to make sure which fields are available at the client side.

### Introspection

Introspection is the ability to query which resources are available in the current API schema. Given the API, via introspection, we can see the queries, types, fields, and directives it supports.

### Query Complexity

limit how deep can your query be nested. for example, if an entity has one-to-many relationship with its own entity, response might be nested forever. You can set this complexity to avoid this issue. 

### Binding

bind a query to an object/struct.
