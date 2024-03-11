# Readings: MongoDB and Mongoose




## [SQL vs NoSQL](https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/?utm_source=tuicool) 
1. **Fill in the chart below with five differences between SQL and NoSQL databases:**
  | **SQL**                                        | **NoSQL**                                            |
* SQL databases are table-based | NoSQL databases can be document-based, key-value pairs, wide-column stores, or graph databases. 
* SQL databases use structured query language for defining and manipulating data. | NoSQL databases use various query languages, often specific to the database type. |
* SQL databases are generally vertically scalable | NoSQL databases are horizontally scalable |
* SQL databases are best suited for complex queries and transactions | NoSQL databases are better suited for hierarchical data storage |
* SQL databases are ACID compliant (Atomicity, Consistency, Isolation, Durability). | NoSQL databases may sacrifice some ACID properties for better scalability and performance. |

3. **What kind of data is a good fit for an SQL database?** Structured data with a predefined schema is a good fit for an SQL database. SQL databases excel in handling relational data where tables are interlinked through defined relationships.

4. **Give a real world example.** A good real-world example of data suitable for an SQL database is an e-commerce platform. It may have tables for customers, orders, products, and transactions. Each table would have well-defined columns and relationships between them.
5. **What kind of data is a good fit a NoSQL database?Give a real world example.**
   * - Semi-structured or unstructured data is a good fit for a NoSQL database. NoSQL databases are suitable for scenarios requiring flexibility in data models and scalability.
   * - A real-world example could be a social media platform like Twitter or Facebook where user-generated content, such as posts, comments, and likes, can vary greatly in structure and volume.
6. **Which type of database is best for hierarchical data storage?** NoSQL databases are typically better suited for hierarchical data storage. Specifically, document-oriented databases like MongoDB are well-suited for storing hierarchical data structures.
7. **Which type of database is best for scalability?** NoSQL databases are generally considered better for scalability due to their distributed architecture and flexible data models. They can easily scale out across multiple servers or clusters to handle increasing amounts of data and traffic.

## Videos
## [sql vs nosql (Video)](https://www.youtube.com/watch?v=ZS_kXvOeQ5Y)

1. **What does SQL stand for?** SQL stands for Structured Query Language.
2. **What is a relational database?** A relational database is a type of database that organizes data into tables with rows and columns. It establishes relationships between these tables using keys.
3. **What type of structure does a relational database work with?** Relational databases work with structured data.
4. **What is a ‘schema’?** A schema in the context of a relational database refers to the structure or blueprint that defines the organization of data in a database, including tables, columns, data types, constraints, and relationships.
5. **What is a NoSQL database?** NoSQL (Not Only SQL) database is a type of database that provides a mechanism for storage and retrieval of data that is modeled in a non-tabular format. It offers more flexibility in data models compared to traditional relational databases.
6. **How does it work?** NoSQL databases typically work by storing data in flexible formats such as key-value pairs, documents, wide-column stores, or graphs. They use various data models to organize and retrieve data based on the requirements of the application.
7. **What is inside of a MongoDB database?** Inside a MongoDB database, data is stored in collections, which are analogous to tables in relational databases. Each collection contains documents, which are JSON-like objects that store data.
8. **Which is more flexible - SQL or MongoDB? and why.** MongoDB is typically considered more flexible than SQL databases because it doesn't require a predefined schema. It allows for dynamic and evolving data structures within documents, making it easier to adapt to changing application requirements.
9. **What is the disadvantage of a NoSQL database?** One disadvantage of NoSQL databases is the lack of standardized query language and ACID (Atomicity, Consistency, Isolation, Durability) properties. Additionally, NoSQL databases may not be suitable for complex transactional operations and may require more effort in data consistency and integrity management compared to SQL databases.



