*RabbitMQ-Learning-Project-Microservice*

This repository contains a learning project focused on building microservices with Spring Boot 3 and RabbitMQ. 
The project was developed as part of the Spring Boot 3 + RabbitMQ Microservices certification course on Udemy.

Overview
The goal of this project is to demonstrate how to integrate RabbitMQ into a microservices architecture using Spring Boot.
It covers essential concepts such as message producers, consumers, queues, exchanges, and routing.

Features
1) Spring Boot 3 for building microservices
2) RabbitMQ for message brokering
3) REST API endpoints for sending and receiving messages
4) JSON message format
5) Asynchronous communication between services
6) Docker support for containerized deployment
7) Error handling and retry mechanisms
8) Logging with SLF4J and Logback

Architecture
The project follows a microservices architecture with the following components:

1) Producer Service: Sends messages to a RabbitMQ exchange.
2) Consumer Service: Listens to the RabbitMQ queue and processes incoming messages.
3) RabbitMQ Broker: Manages message exchanges and queues.
