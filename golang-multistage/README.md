# Go Multi-Stage Docker Build

A multi-stage Dockerfile for compiling a Go application into a minimal final image.

## Usage

1.  **Build the Docker image:**

    ```bash
    docker build -t your-go-app .
    ```

2.  **Run the container:**

    ```bash
    docker run -p 6060:6060 your-go-app
    ```

The application will expose port `6060`.
