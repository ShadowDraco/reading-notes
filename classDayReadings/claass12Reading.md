# CRUD

## Create, read, update, and delete are the main database actions. Knowing how to use them is important for using any database

### [Status Codes Based On REST Methods](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)

In your own words, describe what each group of status code represents:

- 100’s = Status codes that tell the user about something that will or might happen after processing finishes
- 200’s = Success codes that tell the user their request was good
- 300’s = A code that tells users what they are looking for no longer exists and where they should try again
- 400’s = codes that tell the user they did something wrong or something went wrong on their end
- 500’s = codes that tell the user the server did something wrong or something went wrong on their end.

What is a status code 202?

- The data has not finished processing but their request was good at the time of receiving.

What is a status code 308?

- Permanent redirect, tell the user where to go next time because this route is not going to be used any more.

What code would you use if an update didn’t return data to a client?

- 204 No content, just tell the user everything went fine without waiting for the async request to finish or sending back a large body

What code would you use if a resource used to exist but no longer does?

- 410 - used to exist

What is the ‘Forbidden’ status code?

- 403 - unauthorized

[Build A REST API With Node.js, Express, & MongoDB - Quick](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw)

Why do we need to pull our MongoDB database string out of our server and put it into our .env?

- The server needs the connection string to connect to the database. It goes in the .env specifically so that sensitive data can be left out of reach from other people because the server will not be left for localhost.

What is middleware?

- code that runs when the server gets a request, but before it executes the code for the route

What does app.use(express.json()) do?

- middleware allows the server to use and accept json.

What does the /:id mean in a route?

- a "variable" in the query string. It lets the server to listen to non-hardcoded routes by comparing the routes parameters like /user/:id = req.params.id to perhaps a user id in the database

What is the difference between PUT and PATCH?

- PUT is a replace (all), and PATCH is an update (some)

How do you make a default value in a schema?

- add default: (default value) into the value you want to be defaulted:

```javascript
    subscribeDate: {
        type: Date,
        required: true,
        default: Date.now
    }
// allow the date to be passed, but if it's not give it the default value of the date the object was created
```

What does a 500 error status code mean?

- Server side error, the server being called had an error and it is not the fault (usually) of the one calling the server

What is the difference between a status 200 and a status 201?

- 200 is success. 201 is successfully created (from a post route)

## Things I want to know more about

middleware
