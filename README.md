# PeopleProject-SpringBoot

People Project: Spring Boot and PostgreSQL

The People Project is able to instantiate a Person object, and has CRUD operations connecting to a Database. 

The project uses the SpringBoot Framework Annotations such as @RestController, @Transactional and more.
The project implements JpaRepository and uses JPQL.

Project Design:

![alt text](https://github.com/JRyanEv/PeopleProject-SpringBoot/blob/main/Project%20Design.PNG)

Person object has parameters: id, name, email, dob, and age. id is the primary key for the database. Person objects are instantiated in PersonConfig.java

Created using: 
  Spring Initializr: https://start.spring.io/,
  SpringBoot Framework,
  PostgreSQL database running on localhost server,
  Intellij IDE, and 
  Java programming language
  
  ![alt text](https://github.com/JRyanEv/PeopleProject-SpringBoot/blob/main/Project%20Execution%20Example.PNG)
  
  
  
