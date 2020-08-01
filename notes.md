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

* A data source is any database, service or API that holds the data you use to populate the schema's fields

* `DataSource` can extend to handle interaction logic for particular data source

* `RESTDataSource` class is an extension of `DataSource` which can handle fetching data from REST API

* `RESTDataSource` class automatically caches responses from REST resources with no additional setup, this feature is called `partial query caching`
