### DBMS Architecture
1. The DBMS design depends upon its architecture. The basic client/server architecture is used to deal with a large number of PCs, web servers, database servers and other components that are connected with networks.
2. The client/server architecture consists of many PCs and a workstation which are connected via the network.
3. DBMS architecture depends upon how users are connected to the database to get their request done.

### Types of DBMS Architecture

Database architecture can be seen as a single tier or multi-tier. But logically, database architecture is of two types like: 2-tier architecture and 3-tier architecture.

#### 1-Tier Architecture
1. In this architecture, the database is directly available to the user. It means the user can directly sit on the DBMS and uses it.
2. Any changes done here will directly be done on the database itself. It doesn't provide a handy tool for end users.
3. The 1-Tier architecture is used for development of the local application, where programmers can directly communicate with the database for the quick response.

#### 2-Tier Architecture
1. The 2-Tier architecture is same as basic client-server. In the two-tier architecture, applications on the client end can directly communicate with the database at the server side. For this interaction, API's like: ODBC, JDBC are used.
2. The user interfaces and application programs are run on the client-side.
3. The server side is responsible to provide the functionalities like: query processing and transaction management.
4. To communicate with the DBMS, client-side application establishes a connection with the server side.

#### 3-Tier Architecture
1. The 3-Tier architecture contains another layer between the client and server. In this architecture, client can't directly communicate with the server.
2. The application on the client-end interacts with an application server which further communicates with the database system.
3. End user has no idea about the existence of the database beyond the application server. The database also has no idea about any other user beyond the application.
4. The 3-Tier architecture is used in case of large web application.