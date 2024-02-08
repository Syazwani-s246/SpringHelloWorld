# Spring HelloWorld Application

This is a simple Spring Boot application that demonstrates serving static HTML content using Spring MVC.

## Overview

This application serves a single HTML page, `index.html`, when accessed. The HTML page contains a basic "Hello, World!" message.

## Prerequisites

Before running the application, ensure you have the following installed:

- Java Development Kit (JDK) 17 or later
- Maven

## Running the Application

To run the application, follow these steps:

1. Clone this repository to your local machine:

    ```bash
    git clone <repository-url>
    ```

2. Navigate to the project directory:

    ```bash
    cd spring-helloworld
    ```

3. Build the application using Maven:

    ```bash
    mvn clean package
    ```

4. Run the Spring Boot application:

    ```bash
    java -jar target/spring-helloworld-0.0.1-SNAPSHOT.jar
    ```

5. Once the application is running, you can access it in your web browser at [http://localhost:8082/](http://localhost:8082/).

## Project Structure

The project structure is as follows:

- `src/main/java/com/example/helloworld/springhelloworld`: Contains Java source code, including the main application class and controller.
- `src/main/resources/static`: Contains static resources such as HTML, CSS, and JavaScript files.
- `pom.xml`: Maven project configuration file.

## Technologies Used

- Spring Boot: Framework for creating standalone, production-grade Spring-based applications.
- Maven: Dependency management and build automation tool.
- Java: Programming language used for the backend development.
- HTML: Markup language used for creating the web page.

