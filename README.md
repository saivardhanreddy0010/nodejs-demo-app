# Node.js CI/CD Pipeline with GitHub Actions

## Project Overview

This project demonstrates an automated CI/CD pipeline for a Node.js application using GitHub Actions and Docker.

Whenever code is pushed to the `main` branch, GitHub Actions automatically:

1. Installs Node.js dependencies
2. Runs tests
3. Builds a Docker image
4. Logs in to DockerHub securely
5. Pushes the Docker image to DockerHub

## Technologies Used

- Node.js
- Express.js
- Docker
- DockerHub
- GitHub
- GitHub Actions

## Application

The application is a simple Node.js Express web application.

When accessed, it displays:

Hello from Node.js CI/CD Demo App!

## CI/CD Workflow

```text
Developer pushes code
        ↓
    GitHub Repository
        ↓
   GitHub Actions
        ↓
   Install Dependencies
        ↓
      Run Tests
        ↓
    Build Docker Image
        ↓
    DockerHub Login
        ↓
    Push Docker Image
