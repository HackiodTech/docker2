# Full-Stack FastAPI and React Template

Welcome to the Full-Stack FastAPI and React template repository. This repository serves as a demo application for interns, showcasing how to set up and run a full-stack application with a FastAPI backend and a ReactJS frontend using ChakraUI.

## Project Structure

The repository is organized into two main directories:

- **frontend**: Contains the ReactJS application.
- **backend**: Contains the FastAPI application and PostgreSQL database integration.

Each directory has its own README file with detailed instructions specific to that part of the application.

## Docker Setup and Deployment

### Dockerization

Both the frontend and backend applications have been Dockerized for easier deployment and management. Dockerfiles are included in their respective directories (`frontend/Dockerfile`, `backend/Dockerfile`).

### Docker Compose

A `docker-compose.yml` file is provided at the root of the repository. It orchestrates the deployment of the entire application stack, including services for frontend, backend, Traefik reverse proxy, PostgreSQL database, and Adminer for database management.

### Deployment Instructions

1. Clone this repository:
   ```bash
   git clone https://github.com/HackiodTech/docker2.git
   cd docker2

## Getting Started

To get started with this template, please follow the instructions in the respective directories:

- [Frontend README](./frontend/README.md)
- [Backend README](./backend/README.md)

