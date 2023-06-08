# AWS: API, Dynamo and Lambda

[AWS API Gateway Overview](https://www.serverless.com/amazon-api-gateway)

1.  What is Amazon API Gateway?

Amazon API Gateway is a managed service that allows developers to define the HTTP endpoints of a REST API or a WebSocket API and connect those endpoints with the corresponding backend business logic. It also handles authentication, access control, monitoring, and tracing of API requests.

2.  Why is Amazon API Gateway an important part of the Serverless ecosystem?

Within the Serverless ecosystem, API Gateway is the piece that ties together Serverless functions and API definitions. Being able to trigger the execution of a Serverless function directly in response to an HTTP request is the key reason why API Gateway is so valuable in Serverless setups: it enables a truly serverless architecture for web applications.

3.  How does API Gateway integrate with other AWS services?

API Gateway supports direct integrations that can be configured in the API Gateway user interface (or via the API Gateway’s own API) for the following actions:

Invoking an AWS Lambda function.
Invoking another HTTP endpoint, with or without VPC Link.
Making an HTTP call against the API of any AWS service that provides an HTTP API.
Returning a mock response generated within API Gateway without calling out to other services.

[AWS API Gateway](https://aws.amazon.com/api-gateway/)

1.  What are the some benefits of using Amazon API Gateway?

Amazon API Gateway is a fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale.

2.  What two API types might you choose from?

RESTful APIs
WEBSOCKET APIs

[AWS DynamoDB Guide](https://www.dynamodbguide.com/what-is-dynamo-db/)

1.  What is DynamoDB?

DynamoDB is a hosted NoSQL database offered by Amazon Web Services (AWS)

2.  Under what circumstances would you recommend DynamoDB over MongoDB?

Applications with large amounts of data and strict latency requirements, Serverless applications using AWS Lambda

[AWS DynamoDB](https://aws.amazon.com/dynamodb/)

1.  Explain to a non-technical friend how DynamoDB works.

Dynamo is a database that stores data in tables. Its a fully managed and serverless database meaning developers don't have to write a lot of code to use it with their projects because that stuff is already handled
