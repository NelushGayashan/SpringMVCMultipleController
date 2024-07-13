# Spring MVC Multiple Controller Example

This project demonstrates an advanced implementation of a Spring MVC application with multiple controllers, showcasing how to manage and handle multiple controllers effectively.

## Table of Contents

- [Description](#description)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributors](#contributors)
- [License](#license)
- [Additional Information](#additional-information)

## Description

This project expands on the basic example of creating multiple controllers in a Spring MVC application. It includes advanced features such as enhanced dependency injection, comprehensive validation, and more sophisticated view management.

## Features

- Multiple controllers handling different requests
- Advanced dependency injection with Spring
- Comprehensive validation using Spring Validator
- Enhanced view management with JSP pages
- Modular and scalable architecture
- Integration with Spring Boot for easy deployment

## Technologies Used

- Java
- Spring Framework (Spring MVC, Spring Core)
- Maven
- JSP
- Apache Tomcat
- Spring Boot

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/SpringMVCMultipleController.git
    cd yourrepository
    ```

2. **Add dependencies to `pom.xml`:**

    ```xml
    <dependency>
        <groupId>org.springframework</groupId>
        <artifactId>spring-webmvc</artifactId>
        <version>5.1.1.RELEASE</version>
    </dependency>
    <dependency>
        <groupId>javax.servlet</groupId>
        <artifactId>servlet-api</artifactId>
        <version>3.0-alpha-1</version>
    </dependency>
    ```

3. **Build the project using Maven:**

    ```bash
    mvn clean install
    ```

4. **Deploy the project on a server (e.g., Apache Tomcat):**

    - Copy the `war` file generated in the `target` directory to the webapps directory of your Tomcat server.

5. **Start the server:**

    - Start the Tomcat server and navigate to `http://localhost:8080/SpringMVCMultipleController`.

## Usage

1. **Access the home page:**

    Open a web browser and go to `http://localhost:8080/SpringMVCMultipleController`.

2. **Navigate through the application:**

    - Click on the "Spring MVC" link to view the Spring MVC tutorial page.
    - Click on the "Spring Boot" link to view the Spring Boot tutorial page.

## Contributors

- [Nelush Gayashan](https://github.com/NelushGayashan)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Additional Information

### Directory Structure

