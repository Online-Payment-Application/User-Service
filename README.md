# User-Service
This is a micro-service dedeicated for user related functionalities.

## Scope
 - **User Registration** : Enables user to onboard new Users to the platform by creating new user accounts
 - **User Authentication** : Enables user to securely sign in to the platform and using the application. Also lets the user log out.
 - **User Profile Management** : Functionalities for the users to edit their username, phone number and other information
 - **Authorization** : Enables users to access the platform with different permissions(ADMIN/REGULAR) with Role-Based-Access-Control(RBAC)

## Technologies
 - **Database**: PostgreSQL for the benefit ACID properties
 - **Security**: Spring Security for access control, and JWT (JSON Web Tokens) for serverless authentication
 - **Containerization**: Docker for containerization and Kubernetes for deployment and scalability
 - **Logging and Monitoring**: Logback .
 - **Caching**: Redis.
 - **Messaging**: Apache Kafka for asynchronous communication between microservices or handling user notifications.
 - **Testing**:  JUnit and Mockito.
 - **CI/CD)**: GitHub Actions for automated testing and deployment of user service.
 - **Performance Optimization**: VisualVM for profiling, later may be JProfiler or YourKit for profiling and optimizing the performance of your application.

##Requirements
