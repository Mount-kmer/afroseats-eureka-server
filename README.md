# Eureka Service
- This is a Eureka Service for the afroseats microservice application.

#Overview
- This is a Eureka Service for the afroseats microservices architecture. 
It is a service registry that allows microservices to communicate with each other. 
It is a server that holds information about all client-service applications. 
Every microservice registers itself with the Eureka server via the api gateway and pings the server to update its status. The Eureka server knows all the client applications running on each port and IP address. Eureka Server is also known as Discovery Server.

#Prerequisites
- Java 17
- Maven 3.6+
- Docker (optional), for containerization
#Setup
- Clone the repository
- clone the afroseats-api-gateway repository
#Build
- mvn clean install
#Run the Service
- mvn spring-boot:run