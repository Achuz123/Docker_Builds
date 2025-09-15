# Node.js Docker App

A standard Dockerfile for containerizing a Node.js application.

## Usage

1.  **Build the Docker image:**

    ```bash
    docker build -t your-node-app .
    ```

2.  **Run the container:**

    ```bash
    docker run -p 3000:3000 -d your-node-app
    ```

The application will be available at `http://localhost:3000`.
