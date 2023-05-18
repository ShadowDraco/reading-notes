# Data Modeling

## Reading

## [nosql vs sql](https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/?utm_source=tuicool)

-What type of database is the best fit for the complex query intensive environment?

- SQL databases are much better fit for complex queries due to their structure.

What type of database is the best fit for hierarchical data storage?

- NoSQL is best fit for hierarchal data storage due to the key-value-pair format of the data.

Describe the differences in scalability between a SQl and NoSQL database as though you were speaking to a non-technical friend.

- SQL databases are very good at storing massive amounts of data on one very powerful server. Like a table of data with a million rows that scrolls down and down (vertical scaling) NoSQL databases are very good at integrating multiple machines and bearing the load of massive amounts of data across multiple servers, like one of those google server rooms where there are 1000 big computers all next to each other lining the walls and creating a maze. (horizontal scaling)

## [sql modeling techniques]()

Among data tables, what is a one-to-many relationship and how do we “relate” them?

- A one-to-many relationship is the relationship between a table that has many relations with another table, but the 'one' table does not have relations with the 'many' table. For example a store may have many products in a big table full of individual products. The 'products' table will have many relations with the food table, but the food table does not share relations with the products table.

products food
.. ..
.. -> carrots
.. -> potatoes
... <x-- waffles
[there is no reason for waffles to relate back to the products]

Prior to designing your relational database, it might be useful to **_ create diagrams _** of the database tables and their relationships.

-

Explain the difference between a primary and foreign key.

- A primary key is the unique key that is generally once per row of data, and a foreign key is a match between two primary keys (a relation) Each of the related parts will have the same foreign key and the one which is foreign is simply not the primary key for the item you're inspecting

## Videos

## [sql vs nosql](https://www.essentialsql.com/get-ready-to-learn-sql-7-simplified-data-modeling/)

How do we treat keywords and parameters differently in SQL syntax?

- Keywords are capitalized and parameters are lowercased.

Define normalization within the context of schemas and data.

- Normalization is the process of verifying and or making the data fit the blueprint (schema) so there are no errors in the data.

Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.

- one-to-one relations are relationships between data on two tables that have no other connections. For example a user and their \_ID being apart from a second identifying ID. One-to-many is an example of the ID of an item in a store that multiple people may have ordered. The user table does not have the data for this item but multiple users may have a relationship with the product by having the item's id in their 'orders' column. Lastly a many-to-many relationship is a relationship that has multiple relationships on both ends. A user may have multiple pieces of their data like an ide, a role, and an orders all with id's and other data relating between multiple tables.

## Things I want to know more about

- Is there a more precise way to explain primary keys and foreign keys to someone who wouldn't know, without writing a whole paragraph? haha

### Reflection

- im excited to learn about collections and maybe write some raw SQL
