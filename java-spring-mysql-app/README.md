# Java Spring Boot & MySQL Docker Setup

A simple Docker setup for a Java Spring Boot application deployed on Tomcat with a MySQL database.

## Prerequisites

- Docker
- Docker Compose

## Usage

1.  Place your `basedata.sql` file in the root directory.
2.  Run the application using Docker Compose:

    ```bash
    docker-compose up --build -d
    ```

The application will be available at `http://localhost:8081`.
