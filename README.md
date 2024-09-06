# Spring Boot Layered Template with Docker, Flyway, and MySQL


## About

This project is a Spring Boot starter template designed with a layered architectural pattern for building RESTful APIs. It incorporates key technologies such as Docker for containerization, Flyway for database versioning, MySQL as the relational database, and Hibernate for data persistence.

## Technologies Used

- **Spring Boot**: A powerful framework for building Java-based enterprise applications.
- **Docker**: A containerization platform that simplifies the deployment process.
- **Flyway**: A database migration tool that helps version control database schema.
- **MySQL**: A widely used open-source relational database management system.
- **H2**: A open-source in-memory relational database management system.
- **Hibernate**: An object-relational mapping (ORM) framework for Java.

## Project Structure

The project follows a layered architecture to promote modularity and maintainability. The main layers include:

1. **Controller Layer**: Handles incoming HTTP requests, processes them, and returns appropriate responses.
2. **Service Layer**: Contains the business logic, acting as an intermediary between controllers and repositories.
3. **Repository Layer**: Manages data access and interacts with the database.
4. **Model Layer**: Represents the data structure and entities.

## Getting Started

### Prerequisites

1. [Java Development Kit (JDK)](https://www.oracle.com/java/technologies/javase-downloads.html)
2. [Docker](https://www.docker.com/get-started)


## How to Use as a Starter Template

To use this template as a starting point for your Spring Boot project:

1. Clone the repository:

    ```bash
    git clone https://github.com/ungaratto93/layers.git
    ```

2. Replace the existing code with your application-specific logic.
3. Customize the `application.properties` file in the `src/main/resources` directory for your database configuration.
4. Add additional layers or modify the existing ones based on your project requirements.
5. Build and run your customized application.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests for any enhancements or bug fixes.

## License

This project is licensed under the MIT License

