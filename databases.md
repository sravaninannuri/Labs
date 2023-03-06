# DATABASES:

  ## 1) What is the difference between a relational and a non-relational database?
      relational database:
        * A relational database stores data in tables with predefined relationships between them.
      Non relational databases:
        * a non-relational database, or NoSQL database, stores data in a more flexible format, such as document-based, graph-based, or key-value pairs. Non-relational databases are better suited for handling large amounts of unstructured or semi-structured data, while relational databases are more efficient for structured data with well-defined relationships.   
  ## 2) What are indexes?
        Indexes are data structures in databases that help improve query performance by providing a quick way to locate specific rows of data based on the values in one or more columns. They are essentially copies of portions of database tables that are stored separately and optimized for quick access, which can significantly reduce the time needed to search for data.
  ## 3) What are primary keys and secondary keys?
          A primary key in a relational database is a column or set of columns that uniquely identifies each row in a table. It cannot contain null values and is used to ensure efficient access to data. A secondary key, or non-primary key, is a column or set of columns used to create an index for faster access to data. It does not have to be unique but should be selective enough to optimize queries.


 ## 4) What are inner joins and outer joins?
        Inner joins are commonly used when you want to combine data from two or more tables based on a related column where you only want to return the matching rows. Outer joins are used when you want to include all the rows from one table, even if there are no matching rows in the other table.Understanding inner and outer joins can help you retrieve and combine data from multiple tables effectively in a database, and provide powerful insights into the relationships between the data.
  ## 5) What is the difference between DROP TABLE and TRUNCATE TABLE?
          DROP TABLE : 
           * deletes the entire table and all its data.
           * It is a more destructive command
         TRUNCATE TABLE:
          * It deletes only the data in the table, but keeps the table structure intact.  
          * TRUNCATE TABLE is a faster and less destructive operation.
  ## 6) What are the different data types in SQL?
          SQL supports various data types, including:Numeric: This includes integer, decimal, and floating-point numbers.Character: This includes character strings and text data types.Date and time: This includes date, time, and timestamp data types.Boolean: This includes true/false values.Binary: This includes binary large objects (BLOBs) and binary data types.Miscellaneous: This includes data types such as XML, JSON, and arrays.
  ## 7) Explain the WHERE and HAVING clause
         In a database, the WHERE clause and the HAVING clause are used to filter data from a table. However, they differ in terms of when they are applied and what type of filtering they perform.The WHERE clause is used to filter data when querying a table. It is used to specify a condition that must be met for each row in the table. The WHERE clause can be used to filter data based on one or more conditions, and it can use a range of operators, such as equals (=), not equals (<>), greater than (>), less than (<), and so on. 
         Here's an example:
            SELECT * FROM customers WHERE country = 'USA';

         The HAVING clause, on the other hand, is used to filter data based on an aggregate function or a group function. It is used in conjunction with the GROUP BY clause, which groups the data based on one or more columns. The HAVING clause is used to specify the conditions that the aggregated values must meet in order to be included in the result set. The syntax for the HAVING clause is as follows:
                SELECT column1, column2, aggregate_function(column3) FROM table_name GROUP BY column1, column2 HAVING condition;
         The condition in the HAVING clause can be a simple expression or a combination of multiple expressions, using logical operators such as AND and OR. The HAVING 
         
         clause can be used with various types of conditions, such as:
         
         * Comparison operators: =, <>, >, <, >=, <=
         * Aggregate functions: SUM, AVG, MIN, MAX, COUNT
         * Logical operators: AND, OR

          In summary, the WHERE clause is used to filter records based on a condition, while the HAVING clause is used to filter groups based on an aggregate value.







