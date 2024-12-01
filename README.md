# Hello World API - Spring Boot

This project is a simple REST API built with Spring Boot, exposing a single endpoint that returns a "Hello, World!" message in JSON format.

## Technologies

- **Java** (version 11 or higher)
- **Spring Boot** (version 2.x)
- **Maven** (for dependency management)
- **Postman** (to test the API)

## Requirements

- JDK 17
- Maven 4.0.4

## Instructions

### 1. Clone the Repository

Clone the repository to your local machine using Git:

```
git clone https://github.com/SebastianPE0/API_REST---SpringBoot.git
```
### 2. Build and Run the Project
To build and run the project, navigate to the project folder and execute the following command:

```
mvn spring-boot:run
```
This will start the application on port 8080 by default.

### 3. Test the API with Postman
Open Postman and make a GET request to the following URL:

```
http://localhost:8080/api/hello
```
You should receive a JSON response similar to this:
```
{
    "message": "Hello, World!"
}
```
4. Stop the Application
To stop the application, press Ctrl + C in the console where it's running.

Project Structure
src/main/java/com/example/hello_world_api: Contains the source files of the project.
HelloWorldController.java: REST controller that handles the /api/hello endpoint.
src/main/resources: Contains the Spring Boot configuration files like application.properties.
Notes
The project is set up to use Spring Boot with Maven.
For any questions or contributions, feel free to open an issue or submit a pull request.
