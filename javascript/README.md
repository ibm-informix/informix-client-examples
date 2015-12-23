##Pick the right client driver or API for your Node.js Javascript application:

###ibm_db (CLI) driver (DRDA)
- You write your queries as SQL statements, which can include prepared statements.
- Your best choice if your application needs to be ported from DB2 to Informix.
- Does not support Informix extended data types. 
- Uses the DRDA® connection protocols. 

###REST API
- Your best choice if you want direct connections without a client driver. 
- You write queries with the REST API. 
- Supports all Informix data types, including extended data types and user-defined data types. 
- Uses REST API connections through the Informix wire listener.

###MongoDB driver
- Your best choice for applications with JSON data. 
- You write queries with MongoDB commands. 
- Supports all Informix data types, including extended data types and user-defined data types. 
- Uses the MongoDB Wire protocol through the Informix wire listener. 
