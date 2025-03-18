# Building Role Based Access using AI for Java Developers
This is the repository for the LinkedIn Learning course `Building Role Based Access using AI for Java Developers`. The full course is available from [LinkedIn Learning][lil-course-url].

![lil-thumbnail-url]

In this intermediate-level course, instructor Harit Himanshu shows you how to implement a comprehensive role-based access control (RBAC) system inspired by GitHub's permission model using Java, Spring Boot, MongoDB, and Docker. Starting with core domain modeling, learn how to design and implement both personal and organization account structures with their respective permission hierarchies, develop secure authentication flows and resource management APIs, and create sophisticated authorization mechanisms that handle complex scenarios like role inheritance and resource sharing within organizations. Along the way, leverage the power of GitHub Copilot to accelerate development and testing processes, while learning industry best practices for security implementations. By the end of this course, you'll be equipped with the skills you need to build and test a production-ready RBAC system at scale.

Learning objectives
- Implement role-based access control (RBAC) using GitHub's model as a reference, leveraging Java and the Spring Boot framework to create a secure and scalable authorization system.
- Design and implement a MongoDB database schema to efficiently store and manage users, roles, permissions, and resources, utilizing Docker for containerization.
- Create and test comprehensive authentication flows for both personal and organization accounts, ensuring secure user management and access control.
- Develop and validate resource sharing mechanisms within organizations, implementing role hierarchies and permission inheritance patterns.
- Write robust unit and integration tests using the Spring Boot Test framework, ensuring the security system works as expected across all user scenarios.


# Developer Setup
- To ensure everything works, run `mvn clean install` in the root directory.
- To run the application, run `mvn exec:java -Dexec.mainClass="com.ll.App"` in the root directory. This should print out "Hello World!".

## Running the Application
### Starting the Application
1. Build the application:
```bash
mvn clean install
```

2. Start MongoDB:
```bash
docker-compose up -d
```

3. Running all tests
```
mvn clean test
```

4. Start the server:
```bash
mvn spring-boot:run -Dspring-boot.run.main-class=com.ll.App
```

The application will start on port 8080 by default.

## API Documentation
Once the server is running, you can access:
- Swagger UI: http://localhost:8080/swagger-ui/index.html
- OpenAPI JSON: http://localhost:8080/v3/api-docs
- OpenAPI YAML: http://localhost:8080/v3/api-docs.yaml

## Instructor

Harit Himanshu

Cofounder and CTO at BetterMenu

Check out my other courses on [LinkedIn Learning](https://www.linkedin.com/learning/instructors/harit-himanshu).


[0]: # (Replace these placeholder URLs with actual course URLs)

[lil-course-url]: https://www.linkedin.com/learning/
[lil-thumbnail-url]: https://media.licdn.com/dms/image/v2/D4D0DAQGgdcuarTc-2g/learning-public-crop_675_1200/B4DZU_nMwgHIAY-/0/1740528996100?e=2147483647&v=beta&t=mpANNDzx3OeNVM_jFQEZZQaarf9biGmP3mArYg-iMfQ

