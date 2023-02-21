# APIS

## APIS allow us to get organized data from other places and use it in our own code bases

## [API Design Best Practices](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design)

**What does REST stand for?**

- Representational State Transfer

REST APIs are designed around a **resource.**

**What is an identifier of a resource? Give an example.**

- the identifier of a resource is the _URI_ - ( which can identify resources within resources by giving the URL + URN. while a URL only identifies the location of the main resource. )

**What are the most common HTTP verbs?**

- **GET, POSTm PATCH, DELETE**

**What should the URIs be based on?**

- an organized convention for collections and items like /users/{uid}

**Give an example of a good URI.**

- a URI that is concise and leads to a clear and consistent place each time like /users/{id}/orders and /orders/95/items which can display different parts of the same information, coming from different points, and is clear.

**What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?**

- a 'chatty' web api may require too many requests to receive data, or send too many separate resources from requests. It is best to send and request data after _denormalizing_ it or abstracting the data into a larger category. Instead of mapping through a list of items and sending them individually _just send the whole object_

**What status code does a successful GET request return?**

- 200 (OK)

**What status code does an unsuccessful GET request return?**

- 200 (created) 204 (no content) <-- still good

**What status code does a successful POST request return?**

- 201 (created) 200 (OK) 204 (No content)

**What status code does a successful DELETE request return?**

- 204 (no content)

## What I want to know more about

- Should I check for specific codes like 409 (conflict) 404 (not found) 400 (bad request) to my users, or generalize them and display messages that are (probably) the error and (probably) a couple of ways to fix it.
