# KEYS

Keys play an important role in the relational database.

It is used to uniquely identify any record or row of data from the table. It is also used to establish and identify relationships between tables.

## Types of keys:

### 1. Primary key
1. It is the first key used to identify one and only one instance of an entity uniquely. An entity can contain multiple keys, as we saw in the PERSON table. The key which is most suitable from those lists becomes a primary key.

2. In the EMPLOYEE table, ID can be the primary key since it is unique for each employee. In the EMPLOYEE table, we can even select License_Number and Passport_Number as primary keys since they are also unique.

3. For each entity, the primary key selection is based on requirements and developers.

### 2. Candidate key
1. A candidate key is an attribute or set of attributes that can uniquely identify a tuple.

2. Except for the primary key, the remaining attributes are considered a candidate key. The candidate keys are as strong as the primary key.

### 3. Super Key

Super key is an attribute set that can uniquely identify a tuple. A super key is a superset of a candidate key.

### 4. Foreign key

1. Foreign keys are the column of the table used to point to the primary key of another table.

2. Every employee works in a specific department in a company, and employee and department are two different entities. So we can't store the department's information in the employee table. That's why we link these two tables through the primary key of one table.

3. We add the primary key of the DEPARTMENT table, Department_Id, as a new attribute in the EMPLOYEE table.

4. In the EMPLOYEE table, Department_Id is the foreign key, and both the tables are related.

### 5. Alternate key
There may be one or more attributes or a combination of attributes that uniquely identify each tuple in a relation. These attributes or combinations of the attributes are called the candidate keys. One key is chosen as the primary key from these candidate keys, and the remaining candidate key, if it exists, is termed the alternate key.

### 6. Composite key
Whenever a primary key consists of more than one attribute, it is known as a composite key. This key is also known as Concatenated Key.

### 7. Artificial key
The key created using arbitrarily assigned data are known as artificial keys. These keys are created when a primary key is large and complex and has no relationship with many other relations. The data values of the artificial keys are usually numbered in a serial order.