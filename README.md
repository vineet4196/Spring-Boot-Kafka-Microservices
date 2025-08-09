# Spring Boot Kafka Microservices Project

## Overview
This project implements an **event-driven microservices architecture** using **Apache Kafka**. Services communicate asynchronously by producing and consuming events through Kafka topics.

## Features
- **Order Service**: Publishes events when an order is placed.
- **Stock Service**: Consumes order events to update inventory.
- **Email Service**: Consumes order events to send notifications.
- **Multiple Consumers**: Each service can consume different events in parallel.
- **Decoupled Communication**: Services communicate via Kafka topics without direct dependency.

## Tech Stack
- Java, Spring Boot
- Apache Kafka
- Spring Kafka

## Learning Goals
- Implement Kafka producer and consumer in Spring Boot
- Build microservices that communicate asynchronously
- Handle multiple consumers and events
- Understand event-driven architecture benefits
