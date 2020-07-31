# TIL

* Using the enum type

```gql
 enum Size {
    LARGE
    SMALL
 }

```

* For clients to fetch the objects defined in the type definition, we need to define queries in our schema defination so that they can be executed against the data graph, there is a special type called `Query`

* For clients to enable modifying of data, we need to define some mutation, there is a special type called `Mutation`
