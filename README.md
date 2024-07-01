# ToastSQL Database Management System

Database Management System which provides the following features:

- MSSQL-like syntax
- Database and Table creation/dropping
- Constraints: Primary Key, Foreign Key, Unique
- Data insertion and deletion
- Indexing and Unique Indexing
- Selection and Projection
- Index Nested Loop Join
- Aggregate Functions, Grouping data
- Multiple Data Types

The system was implemented using the below technologies:

- Programming Language: Java
- Key-Value Pairs Storing: MongoDB (exclusively for storing, no functions such as Indexing / Document-Based search was used: each Document has 2 fields: "\_id" and "value", these are concatenated strings)
- Storing Metadata: XML (Jakarta EE Binding)

# Configuration

The system is ready to use, the Database Server owner has to replace the "PLACEHOLDER" string in line "ServerThread.java:151" with their own MongoDB connection URL.
