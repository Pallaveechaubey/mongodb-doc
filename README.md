# MongoDB
<img src="https://github.com/Pallaveechaubey/mongodb-doc/assets/159125105/b490e251-3df6-4937-859b-d93e8692fbc6" alt="Alt Text" style="width: 100%;"/>



# Table of Content
1. [MongoDB Overview](#mongodb)
2. [Why Use MongoDB](#why-use-mongodb)
3. [Use Cases](#use-cases)
4. [MongoDB Architecture](#mongodb-architecture)
5. [Data Modeling in MongoDB](#data-modeling-in-mongodb)
6. [Indexing in MongoDB](#indexing-in-mongodb)
7. [Installing MongoDB](#installing-mongodb)
8. [Using MongoDB](#using-mongodb)
9. [Reference](#Reference)

# MongoDB

- MongoDB is a document based database, which internally stores data in the form of
BSON, but we as normal developers can send or receive data in form of JSON,
internally mongodb manages the conversion of JSON-BSON and BSON-JSON
automatically.

- Now when we used to store data in any RDBMS say MySQL, data was stored in tables.
Tables used to represent real life entity. Inside a table, we had many rows. Rows used
to represent one data record. Columns inside table used to represent properties of the
entity.

- Now in mongodb, we store data in form of documents (JSON like).
So here, a real life entity is represented by Collections. What table is for RDBMS is
collections for mongodb. In simple terms, collections are group of JSON documents.
One record in a collection is called as Document. What row is for RDBMS is document
for mongodb.

- A document is nothing but a JSON (internally BSON), a JSON has multiple key-value
pairs. The key of JSON represent the property of the entity. So what column is for
RDBMS, key (from key-value pair) is for mongodb .

# Why use MongoDB

- **Flexible Schema** : MongoDB's document-based model allows for dynamic and flexible schemas, enabling developers to store data of varying structures without needing a predefined schema.
- **Scalability** : MongoDB is designed to scale horizontally across multiple servers, making it suitable for applications with growing data needs.
- **High Performance** : MongoDB's architecture and query optimization techniques result in high performance and low latency, even for large datasets.
- **Rich Query Language** : MongoDB Query Language (MQL) supports powerful queries, including complex aggregations and geospatial queries, allowing for efficient data retrieval.
- **Replication and High Availability**: MongoDB offers built-in replication features to ensure data redundancy and fault tolerance, providing high availability and disaster recovery capabilities.
- **Automatic Sharding**: MongoDB can automatically distribute data across multiple nodes using sharding, enabling horizontal scaling and improved performance.
- **Community Support and Ecosystem**: MongoDB has a vibrant community and a rich ecosystem of tools, libraries, and integrations, making it easy to develop and maintain MongoDB-based applications.

# Use Cases
**Content Management Systems (CMS)**:

- MongoDB's flexible schema is well-suited for managing content in CMS platforms where content structures may vary widely.
- It allows for easy storage and retrieval of multimedia content, such as text, images, and videos.
Example: A news website that needs to store articles, images, and videos with different metadata.
Real-Time Analytics:

- MongoDB's high scalability and real-time data processing capabilities make it ideal for real-time analytics applications.
- It can handle large volumes of data and provide insights into user behavior, trends, and patterns.
Example: A social media platform analyzing user interactions and engagement in real-time.

**Internet of Things (IoT) Data Management**:

- MongoDB's ability to handle diverse data types and its scalability make it suitable for managing IoT data.
- It can store sensor data, device logs, and telemetry data from millions of connected devices.
Example: Smart city projects collecting and analyzing data from sensors deployed across the city for traffic management or environmental monitoring.
Catalog and Product Management:

- MongoDB's document model allows for easy representation of product catalogs with varying attributes and categories.
- It can efficiently manage product information, inventory, and customer reviews.
Example: E-commerce platforms managing product catalogs with millions of products and multiple attributes.
Mobile and Web Applications:

- MongoDB's JSON-like document structure aligns well with the data formats used in mobile and web applications.
- It provides seamless integration with popular programming languages and frameworks.
Example: Mobile applications requiring offline sync and real-time data updates, such as messaging apps or collaborative task managers.
User Profiles and Personalization:

- MongoDB's flexible schema allows for storing and managing user profiles with varying attributes and preferences.
- It can power personalized experiences by storing user preferences, interaction history, and recommendations.
Example: Online platforms delivering personalized content recommendations based on user behavior and preferences.

**Real-Time Analytics**:

- MongoDB's high scalability and real-time data processing capabilities make it ideal for real-time analytics applications.
It can handle large volumes of data and provide insights into user behavior, trends, and patterns.
Example: A social media platform analyzing user interactions and engagement in real-time.
Internet of Things (IoT) Data Management:

- MongoDB's ability to handle diverse data types and its scalability make it suitable for managing IoT data.
It can store sensor data, device logs, and telemetry data from millions of connected devices.
Example: Smart city projects collecting and analyzing data from sensors deployed across the city for traffic management or environmental monitoring.



 ## MongoDB Architecture


### Database:
Think of a database as a big container where you can store different sets of information. It's like a folder on your computer where you keep files related to a specific topic. In MongoDB, a database is where you organize your collections.

### Collection:
A collection is like a folder inside a database. It's where you group similar types of documents together. For example, if you're storing information about different types of animals, you might have a collection called "Animals" where each document represents a different animal.

### Document:
A document is like a single file within a collection. It's where you store specific pieces of information about one thing. Going back to the animal example, each document in the "Animals" collection might represent a different animal, with details like its name, species, age, etc. Documents are like rows in a spreadsheet, but they can hold more complex data.

### Field:
A field is like a label on a piece of information within a document. It's the key part of a key-value pair. For instance, in our animal document, "name" might be a field with the value "Lion", "species" might be a field with the value "Panthera leo", and so on. Fields help organize and describe the data within a document.

### Index:
An index is like a quick reference guide for finding specific information within your documents. Just like an index in a book helps you quickly locate a particular topic, an index in MongoDB helps speed up the process of finding data. It's a data structure that MongoDB uses to optimize search and retrieval operations, making your queries run faster.

## Data Modeling in MongoDB


### Designing MongoDB schemas based on application requirements:
- **Schema:** Think of a schema as a blueprint or plan for how your data will be organized in MongoDB. It defines the structure of your documents, including what fields they will have and what types of data those fields can hold.
- **Application requirements:** This refers to what your application needs to do and how it needs to store and retrieve data. For example, if you're building a social media app, you might need to store user profiles, posts, comments, etc. Your schema should be designed to support these requirements efficiently.

### Embedding vs. Referencing data:
- **Embedding:** Embedding means putting one piece of data inside another. In MongoDB, you can embed documents within other documents. For example, if you have a blog post document, you might embed the comments for that post directly within the post document. This can be useful when the embedded data is small and doesn't change frequently.
- **Referencing:** Referencing means storing a reference or link to another document instead of embedding it directly. For example, instead of embedding comments within a blog post document, you might store the IDs of the comments and then retrieve the comments separately when needed. This can be useful when the referenced data is large or changes frequently.

### Understanding MongoDB's flexible schema:
- **Flexible schema:** Unlike traditional relational databases, MongoDB has a flexible schema, which means that documents in the same collection don't have to have the same structure. This allows you to store different types of data together and easily modify the schema as your application evolves.
- **Benefits:** The flexible schema makes MongoDB agile and adaptable to changing requirements. It allows you to iterate quickly during development and easily accommodate new features or data types without having to redesign your entire database schema.

## Querying in MongoDB

### CRUD Operations: Create, Read, Update, Delete
- **Create:** Adding new data to your MongoDB database. It's like adding a new record to your list of contacts or creating a new document in your database.
- **Read:** Retrieving existing data from your MongoDB database. It's like looking up a phone number in your contacts or reading a book from your library.
- **Update:** Changing existing data in your MongoDB database. It's like editing a contact's information or updating a book's description.
- **Delete:** Removing data from your MongoDB database. It's like deleting a contact from your list or returning a borrowed book to the library.

### Query Operators: $eq, $gt, $lt, $in, $and, $or, etc.
- **$eq:** Matches values that are equal to a specified value. For example, finding all documents where the "age" field equals 30.
- **$gt:** Matches values that are greater than a specified value. For example, finding all documents where the "price" field is greater than 100.
- **$lt:** Matches values that are less than a specified value. For example, finding all documents where the "quantity" field is less than 10.
- **$in:** Matches any of the values specified in an array. For example, finding all documents where the "status" field is either "open" or "pending".
- **$and:** Combines multiple conditions, all of which must be true for a document to be included in the results. For example, finding all documents where the "age" is greater than 18 and the "gender" is "female".
- **$or:** Matches any of the specified conditions, where at least one condition must be true for a document to be included in the results. For example, finding all documents where the "category" is either "electronics" or "clothing".

### Projection and Aggregation
- **Projection:** It allows you to specify which fields to include or exclude from the query results. For example, retrieving only the "name" and "email" fields from a collection of user documents.
- **Aggregation:** Aggregation operations allow you to process and analyze data in MongoDB, such as calculating averages, grouping data, and performing calculations across multiple documents. For example, calculating the total sales revenue for a specific product category.

## Indexing in MongoDB


### Types of Indexes:
- **Single-field Index:** Indexes a single field in a document. It's like creating an index for the "last name" column in a phone book to quickly find people by their last names.
- **Compound Index:** Indexes multiple fields together. It's like creating an index for both "last name" and "first name" columns in a phone book to find people by their full names more efficiently.
- **Multikey Index:** Indexes arrays in documents. It's like creating an index for the "hobbies" field, which contains multiple hobbies for each person in a document, allowing you to quickly find people based on their hobbies.
- **Text Index:** Special index type optimized for searching text content. It's like creating an index for the "description" field in a collection of articles to quickly find articles containing specific keywords.
- **Hashed Index:** Hashes the values of indexed fields. It's like creating an index for the "password" field in a user database to securely store and retrieve passwords.
- **Geospatial Index:** Indexes geographical data. It's like creating an index for the "location" field in a collection of restaurants to quickly find nearby restaurants based on coordinates.

### Index Creation and Management:
- **Creating Indexes:** In MongoDB, you can create indexes using the createIndex() method. You specify the fields to index and any additional options, such as unique constraints or index type.
- **Managing Indexes:** MongoDB provides commands and methods to manage indexes, such as dropping indexes, listing existing indexes, and modifying index options. This allows you to optimize your database performance as your application evolves.

### Indexing Strategies for Optimal Performance:
- **Identify Query Patterns:** Understand the common queries your application performs and create indexes that support those queries. For example, if your application frequently searches for documents by a specific field, create an index on that field.
- **Avoid Over-Indexing:** While indexes can improve query performance, they also consume storage space and can slow down write operations. Avoid creating indexes on fields that are rarely queried or don't significantly improve query performance.
- **Monitor and Tune Indexes:** Regularly monitor your database performance and index usage. Adjust your indexing strategy based on changes in query patterns or performance issues. Consider using tools like MongoDB's Database Profiler to identify slow queries and optimize index usage.

# Installing MongoDB
To install mongoDb your system need to download
```
Link: https://medium.com/@LondonAppBrewery/how-to-download-install-mongodb-on-
windows-4ee4b3493514
```
# Using MongoDB

Open MongoDB in terminal:
Write  ``mongosh``  in your terminal, and it will open the mongodb console.


# List all databases in mongodb

To list all the databases stored in your mongodb we can use the below commands:


```
show dbs;
```

# How to select a particular DB to work on?

To select a particular db and start querying on it we can use
```
use name_of_database;
```


# How to print all the collections stored in a database ?

To print all the collections we can use:
```
show collections;
```


# How to print all the documents of a collection ?

To print all the documents of a collection we can use:
```
db.collectionname.find();
```

# How to create a new database ?
To create a new database we can do:
```
use new_database_name;
```
The ```use``` command creates a new database if there is no already present db with the
same name, otherwise if there is a db with the same name, it just selects it.

Now what will happen is, after creating a DB, if we try to do show dbs; then it will not list
our newly created database. Because, if mondodb sees that there is no valid collection
added in the database, and the db is empty, it doesn’t list it.

# How to add a new collections ?
To create a new collection we can do:
```
db.createCollection("name_of_the_collection")
```
Make sure we execute this command after use some_db_name

In normal RDBMS, while create a table, we have to define what will be the column of
the table. Why we are not defining properties of a collection on mongodb ?
This is because, mongodb doesn’t restrict us by any means for defining documents of a
collection. Two documents of the same collection can posses different type of
properties.

# How to add a new record to a collection ?
To add a new record we can do:
```
db.collectionName.insertOne({key1: value1, key2: value2 ....})
```
## Reference 
-  https://en.wikipedia.org/wiki/MongoDB 
-  https://www.w3schools.com/mongodb/
-  https://www.ibm.com/topics/mongodb
-  https://www.mongodb.com/docs/
