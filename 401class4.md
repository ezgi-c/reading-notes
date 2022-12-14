[Home](/README.md)

# Class 4 - Data Modeling

## nosql vs sql

1. What type of database is the best fit for the complex query intensive environment?  
SQL
1. What type of database is the best fit for hierarchical data storage?  
NoSQL
1. Describe the differences in scalability between a SQl and NoSQL database as though you were speaking to a non-technical friend.  
SQL databases are vertically scalable while NoSQL is horizontally scalable. Vertical scalability involves adding more resources to an existing system to increase its capacity and horizontal scalability involves adding more resources in the form of additional servers, machines etc.

## sql modeling techniques

1. Among data tables, what is a one-to-many relationship and how do we “relate” them?  
A One-to-many relationship is when an entry in one data table can relate to more than one entry in another table. The 'many' entities in the relationship contain the id from the 'one' to establish their relation.

1. Prior to designing your relational database, it might be useful to <ins>create</ins> a <ins>diagram</ins> of the database tables and their relationships.
1. Explain the difference between a primary and foreign key.  
Primary key identifies each row on a table; foreign key identifies a column or set of columns that match a primary key on another table.


## Video: sql vs nosql

1. How do we treat keywords and parameters differently in SQL syntax?
Keywords are reserved words with specific meanings that cannot be used as identifiers. Parameters are used to specify values in an SQL statement.
1. Define normalization within the context of schemas and data.  
Normalization describes the process of organizing data into tables and columns.
1. Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.  

- One-to-one: relationship between two entities where they only relate to each other and no other entity. For example, a mother of one only has one child and the child only has one mother.
- One-to-many: relationship between two entities where one of the entities can relate to more than one instance of the other. For example, one person can have multiple types of hobbies.
- Many-to-many: multiple instances of an entity are associated with multiple instances of another entity. For example, multiple customers on one data table associated with multiple products on another table.

## Bookmark and Review

[sequelize api](https://sequelize.org/master/)

## Reflection

1. What are your learning goals after reading and reviewing the class README?  
- Learn to perform CRUD operations in an SQL database
- Get more familiar with `sequel`
- Learn to model relational data