# GraphQL in a Serverless World - Ray Gesualdo @raygesualdo

[demo](https://github.com/raygesualdo/serverless-graphql-demo)

[raygesualdo.com](raygesualdo.com)

## Architecture is about Tradeoffs

### Serverless = functions as a service

#### Evaluating Serverless
* Pros
   * evented
   * scalable & highly available
   * cost effective (pay for what you use, usually, there are exceptions though)
   * simple development (functional)
   * lower maintenance (DevOps)
* Cons
   * relatively new
   * raw management (now with YAML config)
   * hard resource limits (you don't own the equipment)
   * cold starts and performance (spinning up of containers)
   * logging and monitorability (lacking, hard to get to, Goolge Cloud best)

### GraphQL (specs, NOT framework/library)

type = REST resource

query = get

mutation = change to existing (delete, etc.)

#### GraphQL features

* Graph representation of types and their relationships
* Strongly typed
* Queries and mutations
* Complex data shapes (single network request vs REST post/author/comments 3 requests)
* Introspection (give me all the meta data, documentation)
* Resolvers (make sure data is the correct type)

#### Evaluation GraphQL
* Pros
   * Improved data retrieval
   * Developer experience benefits (GraphiQL)
   * Excellent client libraries (Apollo)
   * Lower bandwidth use
   * Specification, not an implementation
* Cons
   * New and unknown
   * Potential single point of failure
   * Query abuse (asking for more than you actually need, query complexity analysis)
   * Loses inherent REST capabilities (cannot cache)

## Good Architecture has Seams

### Dissecting an Application

* Cloud Provider (Express to AWS/Google/etc.)
* GraphQL Server (Apollo)
* Business Logic


## More to learn
* mutations & subscriptions
* query optimization
* query complexity
* additional type system features
* middleware
* testing
