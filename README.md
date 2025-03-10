# DevOps Graduation Project - DEPI

## Project Overview
This project demonstrates a complete **CI/CD pipeline** using **Jenkins, Docker, Ansible, and Azure Cloud**. The **Spring PetClinic** application is used as a test subject to showcase DevOps best practices.

## Architecture
The project consists of two main services:
1. **Jenkins Server** – Manages the CI/CD pipeline and listens for GitHub webhooks.
2. **PetClinic Application** – The main application, containerized and deployed using Ansible.

## Technologies Used
- **Jenkins** – Automates the CI/CD pipeline
- **Docker & Docker Compose** – Containerizes the application
- **Ansible** – Automates deployment
- **Azure Cloud** – Hosts the infrastructure
- **Prometheus** – Monitors system performance

## CI/CD Pipeline
The Jenkins pipeline automates the following steps:
1. **Testing** – Runs unit tests using Maven.
2. **Build** – Compiles the Spring Boot application into a JAR file.
3. **Docker Image Creation** – Builds a Docker image for the application.
4. **Push to DockerHub** – Pushes the image to DockerHub.
5. **Deployment** – Uses Ansible to deploy the latest version of the application.
