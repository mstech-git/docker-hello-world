# docker-hello-world 🐳

A simple Python Flask application containerized with Docker.

### Tech Stack
Python, Flask, Docker

### How to Run Locally
```bash
# 1. Build the Docker image
docker build -t docker-hello-world .

# 2. Run the container
docker run -p 5000:5000 docker-hello-world
