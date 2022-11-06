## Three schema Architecture

1. The three schema architecture is also called ANSI/SPARC architecture or three-level architecture.

2. This framework is used to describe the structure of a specific database system.

3. The three schema architecture is also used to separate the user applications and physical database.

4. The three schema architecture contains three-levels. It breaks the database down into three different categories.

### Objectives of Three schema Architecture

The main objective of three level architecture is to enable multiple users to access the same data with a personalized view while storing the underlying data only once. Thus it separates the user's view from the physical structure of the database. This separation is desirable for the following reasons:

1. Different users need different views of the same data.

2. The approach in which a particular user needs to see the data may change over time.

3. The users of the database should not worry about the physical implementation and internal workings of the database such as data compression and encryption techniques, hashing, optimization of the internal structures etc.

4. All users should be able to access the same data according to their requirements.

5. DBA should be able to change the conceptual structure of the database without affecting the user's

6. Internal structure of the database should be unaffected by changes to physical aspects of the storage.

### 1. Internal Level

1. The internal level has an internal schema which describes the physical storage structure of the database.

2. The internal schema is also known as a physical schema.

3. It uses the physical data model. It is used to define that how the data will be stored in a block.

4. The physical level is used to describe complex low-level data structures in detail.

The internal level is generally is concerned with the following activities:

1. Storage space allocations.

For Example: B-Trees, Hashing etc.

2. Access paths.

For Example: Specification of primary and secondary keys, indexes
pointers and sequencing.

3. Data compression and encryption techniques.

4. Optimization of internal structures.

5. Representation of stored fields.

### 2. Conceptual Level

1. The conceptual schema describes the design of a database at the conceptual level. Conceptual level is also known as logical level.

2. The conceptual schema describes the structure of the whole database.

3. The conceptual level describes what data are to be stored in the database and also describes what relationship exists among those data.

4. In the conceptual level, internal details such as an implementation of the data structure are hidden.

5. Programmers and database administrators work at this level.

### 3. External Level

1. At the external level, a database contains several schemas that sometimes called as subschema. The subschema is used to describe the different view of the database.

2. An external schema is also known as view schema.

3. Each view schema describes the database part that a particular user group is interested and hides the remaining database from that user group.

4.The view schema describes the end user interaction with database systems.

Mapping between Views
The three levels of DBMS architecture don't exist independently of each other. There must be correspondence between the three levels i.e. how they actually correspond with each other. DBMS is responsible for correspondence between the three types of schema. This correspondence is called Mapping.

#### There are basically two types of mapping in the database architecture:

1. Conceptual/ Internal Mapping
2. External / Conceptual Mapping

#### Conceptual/ Internal Mapping

The Conceptual/ Internal Mapping lies between the conceptual level and the internal level. Its role is to define the correspondence between the records and fields of the conceptual level and files and data structures of the internal level.

#### External/ Conceptual Mapping

The external/Conceptual Mapping lies between the external level and the Conceptual level. Its role is to define the correspondence between a particular external and the conceptual view.