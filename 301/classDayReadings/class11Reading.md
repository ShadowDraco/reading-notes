# Databases

## Databases will let us persist data even better than a local server cache, more securely.

[nosql vs sql](https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/?utm_source=tuicool)

Fill in the chart below with five differences between SQL and NoSQL databases:

<table>
    <tr>
        <th>SQL</th>
        <th>NoSQL</th>
    </tr>
    <tr>
        <td>Relational</td>
        <td>Non-relational</td>
    </tr>
    <tr>
        <td>Table based</td>
        <td>Document based
        <br>
        <sub>key value pair, graph, or wide-column store</sub></td>
    </tr>
    <tr>
        <td>Preferred Schema</td>
        <td>Dynamic Schema</td>
    </tr>
    <tr>
        <td>Structured Query Language</td>
        <td>Unstructured Query Langauge 
        <br><sub>dynamic and varies between databases</sub></td>
    </tr>
</table>

What kind of data is a good fit for an SQL database?
Give a real world example.

- SQL databases are good for big data that will remain structured in a specific way. As well as in high traffic applications which require more stability and vertical scalability. _Amazon uses SQL databases to store massive amounts of data_

What kind of data is a good fit a NoSQL database?
Give a real world example.

- NoSQL is good for applications that need versatility in horizontal scalability and a built in structure for reading and writing data in specific ways to specific _Documents_ defining a user in a NoSQL database will allow you to easily update User.skills[skill].description utilizing hierarchial data storage. I like using NoSql to define users and other data because the database visualizes information the same way I do when I write code, I can reference an object by values in a hierarchal way

Which type of database is best for hierarchical data storage?

- NoSQL

Which type of database is best for scalability?

- SQL (vertical scalability)

[sql vs nosql video ](https://www.youtube.com/watch?v=ZS_kXvOeQ5Y)

What does SQL stand for?

- Structured Query Language

What is a relational database?

- A relational database is one that stores data across multiple tables and gives them relations.

What type of structure does a relational database work with?

- It works with certain assumptions: data is stored in tables fields and entries (record) are strictly formatted to the field it is stored in.
- All data inserted must be normalized (formatted properly despite what extra or missing values are present.)
- Relations are made through managing fields separately, but giving them a relation such as id's for users, products, and orders that will allow information lookup _relating_ to other fields.
- every record is one to one which means everything has its own Unique ID that relates to it so that even when relating data between fields every user is unique and every product is unique when doing _one to many, many to many, etc_ types of lookups.

What is a ‘schema’?

- A Schema is a structure for a type of data in the database

What is a NoSQL database?

- A database that uses documents and dynamic schemas and does now make use of relations

How does it work?

- Data is stored in documents that will store various _collections_ with data organized by flexible and dynamic Schemas. It stores data without relations to create dynamic and easily queryable data. Best for lots of reads and not as many writes

What is inside of a MongoDB database?

- json objects with key value pairs

Which is more flexible - SQL or MongoDB? and why.

- NoSQL is more flexible because there are fewer relations and less strict data formatting.

What is the disadvantage of a NoSQL database?

- Data can be duplicate and is not viable for large vertical scaling. Lookups are easy and storing flexible data is great, but being sure that data is formatted properly and consistent is not always easy.

## Things I want to know more about

Horizontal versus vertical scaling
( Add more servers and merge data ) | ( Improve server capacity )
I understand the difference between the terms. But can MongoDb be used to store only a few well structured schemas (rather than using multiple collections with many schemas) can mongo still perform just as well as a SQL database?
After a certain point using both in tandem would be the best perhaps as he mentioned.
