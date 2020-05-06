# AWS Amplify
## Overview
It’s a JavaScript Library (framework) for developers to quickly configure, manage and create applications with features for AWS cloud.

AWS Amplify has many modules include
* Auth
* Analytics
* Storage
* API
* Caching
* UI components (forms, login forms)
* etc

![](AWS%20Amplify/33D5B535-BA7E-41C3-B172-6A3D975B0AAA.png)



## CLI Installation
```bash
npm install -g @aws-amplify/cli
amplify configure
```

## System Overview Architecture
![](AWS%20Amplify/FCBB3A4E-97F5-45E0-8BAB-B214F06F68B1.png)

**GraphQL Proxy**: A component that runs the GraphQL engine for processing request and mapping them to logical functions for data operations or triggers.

**Operation**: Query, Mutation and Subscriptions

**Action**: A notification to connected subscribers, which is the result of a mutation

**Resolver**: A function that converts the GraphQL payload to the underlying storage system protocol and executes if the caller is authorized to invoke it. They are written in Velocity Template Language (VTL). [Resolver Mapping Template Reference - AWS AppSync](https://docs.aws.amazon.com/appsync/latest/devguide/resolver-mapping-template-reference.html)

**Function**: A function defines a single operation that can be used across pipeline resolvers. Functions can be reused to perform redundant logic throughout the GraphQL proxy.

```bash
amplify console api
```

## References
[AWS Amplify](https://aws.amazon.com/amplify/)
[Amplify Framework Docs](https://docs.amplify.aws/)

#aws #aws/amplify#