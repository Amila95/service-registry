# service-registry
Welcome to the Service Registry repository! This project serves as a service registry using Java Spring Boot and Eureka Server. It allows you to manage and locate various services within a distributed system. This README will guide you through the setup, configuration, and usage of the Service Registry.

### Prerequisites
Before you begin, ensure you have the following:

* Java Development Kit (JDK) 17 or later installed
* Apache Maven build tool
* Git to clone the repository

### Configuration
Clone the repository to your local machine:

`git clone https://github.com/Amila95/service-registry.git
`

cd service-registry
Open the `src/main/resources/application.yml` file and customize the configuration as needed. You might want to modify the server port, instance name, and other Eureka settings.

### Running the Application
To run the Service Registry, use the following command: `mvn spring-boot:run`

This will start the Eureka Server, and it will be accessible at http://localhost:8761.
