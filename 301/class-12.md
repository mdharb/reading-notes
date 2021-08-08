# **Mongo and Mongoose**

## SQL & NoSQL

***

|      SQL               |              NoSQL                          |
| :---------:            |             :---------:                     |
|called as Relational Databases                        |called as non-relational or distributed database.|
|table based databases                          | document based, key-value pairs, graph databases or wide-column stores|
|databases have predefined schema                      | have dynamic schema for unstructured data|
|vertically scalable                                   |horizontally scalable             |
|Good fit for the complex query intensive environment  |not good fit for complex queries|

***

1. **What kind of data is a good fit for an SQL database?**
   * Fit for heavy duty transactional type applications

2. **Give a real world example**
   *MySql, Oracle, Sqlite, Postgres and MS-SQL.

3. **What kind of data is a good fit a NoSQL database?**
   * Large data set. Hierarchical data storage.

4. **Give a real world example.**
   * MongoDB, BigTable, Redis, RavenDb, Cassandra, Hbase, Neo4j and CouchDb.

5. **Which type of database is best for hierarchical data storage?**
   * NoSQL database.
*
6. **Which type of database is best for scalability?**
   * SQL databases.

***

1. **What does SQL stand for?**
   * Structured Query Language.

2. **What is a realational database?**
   * A type of database that stores and provides access to data points that are related to one another.

3. **What type of structure does a relational database work with?**
   * The structure of a relational database is stored in the data dictionary tables of the database.

4. **What is a ‘schema’?**
   * A collection of database objects.

5. **What is a NoSQL database?**
   * Not only SQL is an approach to database design that enables the storage and querying of data outside the traditional structures found in relational databases.

6. **How does it work?**
   * Relational databases rely on tables, columns, rows, or schemas to organize and retrieve data. In contrast, NoSQL databases do not rely on these structures and use more flexible data models.

7. **What is inside of a Mongo database?**
   * MongoDB makes use of records which are made up of documents that contain a data structure composed of field and value pairs. Documents are the basic unit of data in MongoDB.

8. **Which is more flexible - SQL or MongoDB? and why.**
   * MongoDB is more flexible and ensures high and diverse data availability. 
Data in MongoDB has a flexible schema. Collections do not enforce document structure by default. This flexibility gives you data-modeling choices to match your application and its performance requirements. MongoDB provides the capability for schema validation during updates and insertions.

9. **What is the disadvantage of a NoSQL database?**
   * NoSQL databases don't have the reliability functions which Relational Databases have (basically don't support ACID).