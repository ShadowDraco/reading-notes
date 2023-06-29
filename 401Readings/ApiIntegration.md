# API Integration

## [Review API Server Build](https://codefellows.github.io/code-401-javascript-guide/curriculum/apps-and-libraries/api-server/)

1. Explain the different between a query string parameter and a path parameter.

a query string parameter is a piece of the url that is mapped to a variable in the request. The path parameter is the part of the URL

2. What would our API URL with a path id parameter be given the following information:

   1. Domain: `http://our-site.com`
   2. `v3`
   3. model name: `stuff`
   4. id: `things`

   `v3/stuff/things`

3. We have created a dynamic API with an "interface". Describe how that interface works to a non-technical friend.

An interface is a middle ground between the functions in the server that handle requests, and the parts of the database that those functions connect to. The interface creates generic, reusable, functions that are common to multiple parts of the database and therefore reduces the repetition in the code.

## [Review Auth Server Build](https://codefellows.github.io/code-401-javascript-guide/curriculum/apps-and-libraries/auth-server/)

1. Describe how you would use middleware to implement basic and bearer auth.

To implement basic and bearer auth middleware I would import the middleware functions into the api routes, like v2 (auth protected) and include that middleware into the parameters of the express route handler (including arguments for ACL through currying)

2. Describe the handshake necessary to implement OAuth.

To implement OAuth we need to give the client-id and client-secret, this allows OAuth to verify the client. OAuth then gives us back a jsonWebToken that carries our information and allows us to make requests without having to authenticate again.

3. Describe how Role Based Access Control works to a non-technical friend.

Role based Access control provides authorization for users to do certain tasks based on their role. Role is provided by administrators of the system and therefore bars anyone who is not authenticated OR authorized to do certain tasks

## Reflection

It will be nice to revisit the auth server implementations and learn more.
