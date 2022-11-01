Query optimization is of great importance for the performance of a relational database, especially for the execution of complex SQL statements. A query optimizer decides the best methods for implementing each query.

The query optimizer selects, for instance, whether or not to use indexes for a given query, and which join methods to use when joining multiple tables. These decisions have a tremendous effect on SQL performance, and query optimization is a key technology for every application, from operational Systems to data warehouse and analytical systems to content management systems.

#### There is the various principle of Query Optimization are as follows −

1. Understand how your database is executing your query − The first phase of query optimization is understanding what the database is performing. Different databases have different commands for this. For example, in MySQL, one can use the “EXPLAIN [SQL Query]” keyword to see the query plan. In Oracle, one can use the “EXPLAIN PLAN FOR [SQL Query]” to see the query plan.

2. Retrieve as little data as possible − The more information restored from the query, the more resources the database is required to expand to process and save these records. For example, if it can only require to fetch one column from a table, do not use ‘SELECT *’.

3. Store intermediate results − Sometimes logic for a query can be quite complex. It is possible to produce the desired outcomes through the use of subqueries, inline views, and UNION-type statements. For those methods, the transitional results are not saved in the database but are directly used within the query. This can lead to achievement issues, particularly when the transitional results have a huge number of rows.

#### There are various query optimization strategies are as follows −

1. Use Index − It can be using an index is the first strategy one should use to speed up a query.

2. Aggregate Table − It can be used to pre-populating tables at higher levels so less amount of information is required to be parsed.

3. Vertical Partitioning − It can be used to partition the table by columns. This method reduces the amount of information a SQL query required to process.

4. Horizontal Partitioning − It can be used to partition the table by data value, most often time. This method reduces the amount of information a SQL query required to process.

5. De-normalization − The process of de-normalization combines multiple tables into a single table. This speeds up query implementation because fewer table joins are required.

6. Server Tuning − Each server has its parameters and provides tuning server parameters so that it can completely take benefit of the hardware resources that can significantly speed up query implementation.
