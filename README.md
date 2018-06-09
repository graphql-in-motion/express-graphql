# graphql-in-motion_express-graphql

This serves as a modified version of the `express-graphql` package that has native support for subscriptions. Unfortunately, the [express-graphql](https://github.com/graphql/express-graphql), package does not have support for subscriptions. Support was introduced in [express-graphql/#436](https://github.com/graphql/express-graphql/pull/436), however movement on the PR has been stagnant. 

_This is intended as a drop-in replacement for the package until the functionality introduced in [#436](https://github.com/graphql/express-graphql/pull/436) has been released._

### Installation
```
yarn add graphql-in-motion_express-graphql
```

#### server.js
```
import graphqlHTTP from 'graphql-in-motion_express-graphql'; 
```
