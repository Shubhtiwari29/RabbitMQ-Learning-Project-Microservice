*RabbitMQ-Learning-Project-Microservice*
This repository contains a learning project focused on building microservices with Spring Boot 3 and RabbitMQ. The project was developed as part of the Spring Boot 3 + RabbitMQ Microservices certification course on Udemy.

Overview
The goal of this project is to demonstrate how to integrate RabbitMQ into a microservices architecture using Spring Boot. It covers essential concepts such as message producers, consumers, queues, exchanges, and routing.

Features
Spring Boot 3 for building microservices
RabbitMQ for message brokering
REST API endpoints for sending and receiving messages
JSON message format
Asynchronous communication between services
Docker support for containerized deployment
Error handling and retry mechanisms
Logging with SLF4J and Logback

Architecture
The project follows a microservices architecture with the following components:

Producer Service: Sends messages to a RabbitMQ exchange.
Consumer Service: Listens to the RabbitMQ queue and processes incoming messages.
RabbitMQ Broker: Manages message exchanges and queues.
