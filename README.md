# dgraph


# Development

The Dgraph [quick start guide](https://dgraph.io/docs/graphql/quick-start/) is repeated below

- Pull the Dgraph Docker Image and run it
- Load the schema

```sh
docker run -it -p 8080:8080 dgraph/standalone:master
```

In a new terminal window

```sh
curl -X POST localhost:8080/admin/schema --data-binary '@schema.graphql'
```