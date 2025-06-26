# Api-CRUD-Pokemon

API with simple CRUD operations for a One-To-Many relationship developed for college class.

The system is based on two classes, Pokemon and Trainer, connected to each other in a One-To-Many relationship. A Pokemon is not allowed to have more than one trainer (error is thrown if attempting to attach a Pokemon with a Trainer to another Trainer), but can exist without having a trainer (null). 

Use Springboot initializer with the following specifications:

    Maven 
    Java 3.5.0 
    Jar 17

Dependencies:

    Spring Web 
    Spring Data JPA 
    PostgresSQL 
    Driver 
    Lombok 
    Spring Boot DevTools 
    H2
    
Project listens to port 9090

Linkeding post: https://www.linkedin.com/feed/update/urn:li:activity:7343797583351312384/
