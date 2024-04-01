

# Reading 11 - MongoDB and Mongoose

## Things I want to know more about

### nosql vs sql
1. 5 differences between sql and nosql
- SQL databases have predefined schema whereas NoSQL databases have dynamic schema for unstructured data.
- SQL databases are vertically scalable whereas the NoSQL databases are horizontally scalable
- SQL databases are good fit for the complex query intensive environment whereas NoSQL databases are not good fit for complex queries.
- Excellent support are available for all SQL database from their vendors. For some NoSQL database you still have to rely on community support
- SQL databases emphasizes on ACID properties ( Atomicity, Consistency, Isolation and Durability ) whereas the NoSQL database follows the Brewers CAP theorem ( Consistency, Availability and Partition tolerance )
2. What kind of data is a good fit for an SQL database?
- structured data 
3. Give a real world example.
- a video game - with objects that interact with each other
4. What kind of data is a good fit a NoSQL database?
- unstructured data
5. Give a real world example.
- a personal contact database
6. Which type of database is best for hierarchical data storage?
- NoSQL databases
7. Which type of database is best for scalability?
- NoSQL databases

### sql vs nosql (video)
1. What does SQL stand for?
- Structured Query Language
2. What is a relational database?
- a type of database that has data that relates to other data point
3. What type of structure does a relational database work with?
- tables
4. What is a ‘schema’?
- the logical and visual configuration of the entire relational database
5. What is a NoSQL database? How does it work?
-  they use a non-tabular format to store data rather than in rule-based, relational tables. NoSQL databases use a flexible schema model that supports a wide variety of unstructured data
6. What is inside of a MongoDB database?
- unstructured JSON data
7. Which is more flexible - SQL or MongoDB? and why.
- MongoDB (NoSQL) is more flexible because of its schema and lack of relationships between data
8. What is the disadvantage of a NoSQL database?
- lack of standardization, lack of ACID: Atomicity, Consistency, Isolation, and Durability
