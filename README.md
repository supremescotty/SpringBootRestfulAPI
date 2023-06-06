# SpringBootRestfulAPI
 simple API for a fictional online store or a book library, where users can retrieve, post, update and delete data. Demonstrates my understanding of the HTTP protocol, as well as CRUD operations.


The @ResponseStatus(HttpStatus.NOT_FOUND) annotation causes Spring boot to respond with a 404 NOT FOUND status when this exception is thrown.

Spring Security dependency to your pom.xml or build.gradle requires the client to provide a valid username and password with every request. The passwords should be stored in the database in a hashed format, which is where BCryptPasswordEncoder comes in.
