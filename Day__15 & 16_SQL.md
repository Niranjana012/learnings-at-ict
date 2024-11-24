## 1. What is a Database and its Types?  
  A database is a structured collection of data that is stored and accessed electronically.    
  Databases are designed to store, manage, and retrieve data efficiently.        
  There are different types of databases, classified based on their structure, the nature of the data they store, and how they are used.

### Types of Databases:

Relational Database (RDBMS): Stores data in tables (rows and columns) and uses SQL for querying. Examples: MySQL, PostgreSQL, Oracle, Microsoft SQL Server.
  
NoSQL Database: Stores data in formats other than tables (e.g., key-value pairs, documents, graphs). Examples: MongoDB (document-based), Redis (key-value), Neo4j (graph-based).
  
Object-Oriented Database: Stores data in objects (similar to how programming languages like Java and C++ handle data). Examples: db4o, ObjectDB.
  
Hierarchical Database: Organizes data in a tree-like structure, where each child node has only one parent. Example: IBM's IMS.
  
Network Database: Similar to hierarchical databases but allows more complex relationships. Example: Integrated Data Store (IDS).
  
Distributed Database: A database where data is stored across multiple physical locations. Example: Apache Cassandra.

### What is SQL?
SQL (Structured Query Language) is a standardized programming language used for managing and manipulating relational databases.    
It enables users to perform tasks like querying data, inserting, updating, and deleting records, as well as managing database structures.  

### Relational Databases examples

#### 1. Relational Databases (RDBMS)
Relational databases store data in tables with rows and columns, and relationships between tables are managed using keys (primary, foreign, etc.).  
They use SQL for querying.

MySQL: An open-source relational database management system. Used in web applications, it's one of the most popular databases.      
Example Usage: A website using a MySQL database for storing user data, posts, and comments.

PostgreSQL: An advanced open-source relational database system that supports a wide range of data types and advanced querying features.      
Example Usage: A financial application using PostgreSQL to store transaction records and customer information.

Oracle Database: A commercial relational database system known for its robustness and scalability, commonly used in large enterprise applications.     
Example Usage: A multinational corporation using Oracle Database for managing sales data, customer relationships, and inventory.

Microsoft SQL Server: A relational database developed by Microsoft, often used in enterprise environments and compatible with .NET applications.      
Example Usage: A company using SQL Server for employee records, payroll systems, and project management data.

#### 2. Non-Relational Databases (NoSQL)
Non-relational databases are used for large-scale data storage that does not fit neatly into tables with rows and columns. They are flexible and scalable.

MongoDB: A document-based NoSQL database that stores data in flexible, JSON-like documents.      
Example Usage: A social media app storing user profiles, posts, and comments in a MongoDB database.

Cassandra: A wide-column store that is highly scalable and optimized for handling large amounts of data across distributed systems.     
Example Usage: A global e-commerce platform using Cassandra for managing product catalogs, inventory, and user sessions.

Redis: A key-value store that works well for caching and real-time applications.      
Example Usage: A gaming app using Redis to store user session data and real-time game state information.

Neo4j: A graph database used for storing and querying graph data, where relationships between entities are as important as the data itself.     
Example Usage: A social network using Neo4j to represent and query the connections between users, such as friendships and followers.

#### 3. Object-Oriented Databases
Object-oriented databases store data in the form of objects, similar to how programming languages like Java and C++ work with objects.         

db4o: A database that allows storing complex data in the form of objects and provides automatic handling of object persistence.           
Example Usage: A CAD software that stores 3D models and configurations as objects within the database.

ObjectDB: A high-performance object-oriented database used with Java applications.            
Example Usage: A stock trading application that stores market data and user portfolios as objects in the database.

#### 4. Hierarchical Databases
Hierarchical databases organize data in a tree-like structure where each child record has one parent.

IBM IMS: A hierarchical database system used in large enterprises, especially in banking and finance.           
Example Usage: A banking system using IMS to manage customer accounts, transactions, and relationships between them.

#### 5. Distributed Databases
These databases store data across multiple physical locations, ensuring redundancy, reliability, and scalability.

Apache Cassandra: A distributed NoSQL database designed for scalability and high availability without a single point of failure.
Example Usage: A global social media platform using Cassandra to handle user data across multiple regions.

Amazon DynamoDB: A fully managed, distributed NoSQL database service offered by AWS.
Example Usage: An online retailer using DynamoDB to store shopping cart data and product catalogs.

#### 6. Cloud Databases
Cloud databases are hosted and managed on cloud platforms, providing scalability, remote access, and reduced overhead.

Google Cloud Firestore: A NoSQL database for storing data in the cloud, commonly used in mobile and web apps.
Example Usage: A mobile app storing user data and app preferences in Firestore.

Amazon RDS (Relational Database Service): A cloud service by AWS for managing relational databases like MySQL, PostgreSQL, and Oracle.
Example Usage: A startup using Amazon RDS to host their MySQL database for customer and product information.

#### 7. Examples of Structured and Unstructured Databases
Structured Database:
Example: A relational database like MySQL or PostgreSQL is an example of a structured database, where the data is highly organized and stored in tables with rows and columns.

Unstructured Database:
Example: MongoDB (document-based) or Hadoop HDFS (storing large amounts of raw data) are examples of unstructured databases, 
where data can vary in format (e.g., JSON, logs, images, videos) and doesn’t require a strict schema.  

### Execution Flow of SQL Queries

When an SQL query is executed, the following steps typically occur:

#### Parsing: 
The SQL engine parses the query to check if the syntax is correct.         
If there is a syntax error (e.g., a misspelled keyword or a missing comma), the engine returns an error.

#### Optimization:
The SQL engine evaluates the most efficient way to execute the query.     
This involves analyzing indexes, available joins, and data distribution.

#### Execution: 
Once the query is optimized, the database engine executes the operations.      
For example, if it’s a SELECT query, it will retrieve the data; if it’s an INSERT query, it will add data to a table, etc.

#### Result:
The result is returned to the user or application, or the database state is modified (e.g., data is updated or deleted).

### SQL Logical Operators:

#### AND: 
Combines conditions; all conditions must be true.
#### OR:
Combines conditions; any condition can be true.
#### NOT:
Negates the condition.
#### BETWEEN:
Filters data within a specified range.
#### IN: 
Matches any value within a list.
#### LIKE: 
Used for pattern matching.
#### IS NULL / IS NOT NULL: 
Checks if a column contains NULL values.
#### EXISTS: 
Tests if a subquery returns any results.

### SQL Joins: 
 used to combine rows from two or more tables based on a related column between them.

#### 1. INNER JOIN
The INNER JOIN returns rows when there is a match in both tables. If there is no match between the tables, the row will not be included in the result set.

#### 2. LEFT JOIN (or LEFT OUTER JOIN)
The LEFT JOIN (or LEFT OUTER JOIN) returns all rows from the left table, and the matching rows from the right table.     
If there is no match, NULL values are returned for columns from the right table.

#### 3. RIGHT JOIN (or RIGHT OUTER JOIN)
The RIGHT JOIN (or RIGHT OUTER JOIN) is the opposite of a LEFT JOIN.        
It returns all rows from the right table, and the matching rows from the left table.    
If there is no match, NULL values are returned for columns from the left table.

#### 4. FULL JOIN (or FULL OUTER JOIN)
The FULL JOIN (or FULL OUTER JOIN) returns all rows when there is a match in either left or right table.      
If there is no match, NULL values are returned for the missing side.

#### 5. CROSS JOIN
The CROSS JOIN returns the Cartesian product of the two tables.           
That means it returns all possible combinations of rows from both tables. There is no ON condition with a CROSS JOIN.

#### 6. SELF JOIN
A SELF JOIN is a join where a table is joined with itself. This is useful when you have hierarchical or recursive data in the same table.

#### 7. NATURAL JOIN
A NATURAL JOIN automatically joins tables based on columns with the same name and compatible data types.          
You do not have to specify the column to join on, as it automatically finds columns with the same name.
