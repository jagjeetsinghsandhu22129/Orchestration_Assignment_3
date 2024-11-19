# Orchestration_Assignment_3




## Overview
This project demonstrates the use of Docker Compose to orchestrate multiple containers. It includes:
- A web service built with Python Flask that displays a configurable message.
- An NGINX-based load balancer to distribute traffic across multiple web service instances.

## Features
- **Web Service**: Displays a message set via environment variables.
- **Load Balancer**: Routes traffic between two instances of the web service.
- **Single Command Deployment**: Easily deploy all services using Docker Compose.

## Prerequisites
- Docker and Docker Compose installed on your system.

## How to Run
1. Clone the repository or download the project files.
2. Navigate to the project directory:
   
   cd Orchestration_Assignment_3

 docker-compose up --build

 ## Clean Up

 docker-compose down