# My First Docker App

A simple Flask web app running inside a Docker container.

## What I learned
- How to write a Dockerfile
- How to build a Docker image
- How to run a container
- How to expose a port

## Tech used
- Python
- Flask
- Docker

## How to run it yourself
docker build -t ahmed-first-app:1.0 .
docker run -p 8080:5000 ahmed-first-app:1.0

Then open http://localhost:8080