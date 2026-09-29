# Docker Learning

This repository contains my hands-on learning and practice with **Docker** and **Docker Compose**, covering core containerization concepts, Docker images, networking, persistent storage, registries, and essential Docker commands.

## Topics Learned

### Docker Fundamentals

* What is Docker
* Containers
* Where containers run
* Benefits of containers in development
* Benefits of containers in deployment
* Docker architecture and components
* Docker Image
* Docker Image vs Container
* Docker vs Virtual Machine
* Container Port vs Host Port

### Docker Commands

* `docker pull`
* `docker run`
* `docker start`
* `docker stop`
* `docker ps`
* `docker ps -a`
* `docker logs`
* `docker exec`
* `docker rm`
* `docker rmi`
* `docker images`
* `docker build`

### Docker Networking

* Docker Networks
* Container-to-container communication
* User-defined bridge networks
* Docker DNS
* Container names and service names
* Container ports vs published host ports

### Dockerfile

* Dockerfile
* `FROM`
* `WORKDIR`
* `COPY`
* `RUN`
* `EXPOSE`
* `CMD`
* Dockerfile build process
* `RUN` vs `CMD`

### Docker Image

* Image creation
* Image naming
* Image tags
* Image layers
* Build cache
* Image removal

### Docker Registry

* Docker Registry
* Docker Hub
* Image naming in registries
* Registry / Namespace / Repository / Tag
* `docker login`
* `docker tag`
* `docker push`
* `docker pull`

### Docker Volumes

* Docker Volumes
* Persistent storage
* Named volumes
* Volume creation
* Volume mounting
* Volume inspection
* Volume removal
* Volume persistence with containers
* Volumes with Docker Compose

### Docker Compose

* Docker Compose
* `docker-compose.yml` / `compose.yml`
* Compose services
* `docker compose -f`
* `docker compose up`
* `docker compose down`
* Detached mode with `-d`
* Compose networks
* Compose service communication
* Compose volumes

### Additional Docker Concepts

* `.dockerignore`
* Docker image layers
* Docker build cache
* Docker `HEALTHCHECK`
* Container health states
* Basic Docker troubleshooting
* Container logs and debugging

## Learning Flow

```text
Dockerfile
    ↓
Docker Build
    ↓
Docker Image
    ↓
Docker Registry
    ↓
Docker Pull
    ↓
Docker Container
    ↓
Docker Network
    ↓
Docker Volume
    ↓
Docker Compose
```

## Practical Project Context

The concepts learned here are being applied to a multi-container application involving:

```text
Frontend
   ↓
Node.js Backend
   ↓
MongoDB
```

Docker Compose is used to understand how multiple application services can be configured, networked, and managed together.

## Goal

Build a strong foundation in Docker containerization and understand how Docker is used in real-world application development, deployment, and CI/CD workflows.
