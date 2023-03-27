# graphql
Learning GraphQL

Query language for an API.

Features - 

We can ask for what we need and get exactly that. The client has full control over which data it wants from server. But with restful APIs we get all data from server, which results in over fetching.
Again, for fetching two different resources we need to make separate calls in rest, but in graphQL we can hit multiple resources with single request. 
Giving schema which gives structure of API. Clear contract between server and client.
Evolving API without versions.
GraphQL can be a layer over your code. It can expose the endpoint for your API.

Useful tools - GraphiQL

Package Required - 

apollo-server - This is used for serving over http
graphQL - This has the core graphQL functionalities 

"gql" = It helps in validating the schema. 

Notes - 

1. In GraphQL, we always make a POST request