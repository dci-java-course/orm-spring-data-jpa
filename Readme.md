# Exercise # 2 - Spring Data JPA


In this exercise you'll create a data access layer for a domain object Customer.

1. Create a customer table in your mysql database with 3 fields in it.
	- id (int)
	- name (varchar)
	- email (varchar)


2. Create a spring project boot named customerdata using one of the spring boot project creation method
  - (start.spring.io, IDE or CLI)


3. Once you have the spring boot project, create an entity or model class which you'll map to the database table using JPA annotations.
  - Create fields within this entity namely id, name and email which will be automatically mapped to id, name and email in the database table.
  - If the names here are different from database, you should use annotations like @Column. But if field names are same as the database table column names, no additional annotations are required.
  - Mark the id attribute as primary key


4. Create a Customer Repository	that will extend the CrudRepository Interface.


5. Configure the datasource in the application.properties file(spring boot properties file)


6. Write tests to perform CRUD operation on the customer entity.
	- Write 4 different tests to verify the
      - save,
      - update,
      - delete and
      - read/find  
      operations can be done using Customer Repository.
