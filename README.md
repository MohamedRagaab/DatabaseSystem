# Database Management System (DBMS) 

## DBMS
* It provides efficient, reliable, convenient and safe multi-user storage of and access to massive amounts of persistent data.
  * Massive
  * Persistent
  * Safe
  * Multi-user
  * Convenient
  * Efficient
  * Reliable 
* Database applications ma be programmed via "frameworks"
* DBMS may run in conjunction with "middleware"
* Data-intensive appications may not use DBMS at all.

### Key concepts
* Data Model 
  * How data is structured (General form of data that is stored in the database).  
* Schema Versus data
  * schema is the types and data is the variables. 
* Data definition language (DDL)
  * Setup schema strudcure. 
* Data manipulation or quary language (DML)
  * Quaring and modifing.

### Key People
* DBMS implementer
  * Builds system.
* Database designer
  * Establish schema.  
* Database application developer
  * programs that operate an the database.
* Database administrator
  *  Loads data, keeps running smookly.
 
## The Relational Model
* Used b all major commercial database systems
* Very simple model
* Query with high-level languages: simple yet expressive
* Efficient implementations
### Basic Construct of Relational Model
* Database = set of named relations(or tables)
* Each relation has a set of named attributes (or columns)
* Each tuple (or row) has a value for each attribute
* Each attribute has a type (or domain)
* Schema is a structural description of relations in database
* Instance actual contents at given point in time
* Null i a special value for "unkown" or "undefiend"
* Key is an attribute whose value is unique in each tuple or a combined values are unique
### Creating relations (tables) in SQL
* Create Table Student (ID, name, GPA, photo)
* Create Table Collage (name string, state char(2), enrollment integer)
## Quering Relational Database
* steps in creating and using a (relational) database
* Design schema; create using DDL
* "Bulk load" initial data
* Repeat: execute queries and modifications










