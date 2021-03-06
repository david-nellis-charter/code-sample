# Charter Enterprise MOTD Sample Project
A small project to help assess candidate experience with webservices and our technology stack.

## Instructions
We have provided a webservice that provides a "message of the day", similar to what you might see logging into a Unix system. Unfortuantely, at Charter things don't always go as planned and we need to change the message.  We need you to add the ability to change the message.   The message can be stored in the service using any mechanism you like, but aim for simplicity.  Something very simple, and in memory can be used.   It does not have to be durable between restarts, so please avoid writing to a file.  A persistent store like MySQL or Hypersonic could be overkill for this new requirement.  Iterative requests for the MOTD should return the new message, if it has been changed. Be sure to edit this README.md so we understand what you've done.

Also, a rogue developer has left the code base broken.  To get anything done, you're doing to have to fix the tests first! And, no, -DskipTests is not a solution!

### To submit your solution
Push your answer to this Github repo as a feature branch and create a pull request to master so we know you're done.

### Getting Started
* To compile
```mvn clean package```

* To run
```mvn spring-boot:run```

* To see the message:
```curl localhost:8080```

### Prerequisites
* Java 1.8
* Maven
* cURL
  
### Project hints and questions
* Stuck getting started?
  * The official Spring Boot "hello world" example is a great starting point.
* Still need help?
  * Further hints are available, Feel free to ask questions here.  Edit this file in your branch by adding to the questions section, push it, and we will update the file with answers. 