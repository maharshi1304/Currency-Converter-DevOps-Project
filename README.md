# Currency Converter DevOps Project

## Overview

This project demonstrates a complete CI/CD deployment workflow for a Dockerized Currency Converter web application using GitLab CI/CD, Docker, Docker Hub, and AWS EC2 with a self-hosted GitLab Runner.

---

## Tech Stack

- HTML
- CSS
- JavaScript
- Docker
- Docker Compose
- GitLab CI/CD
- GitLab Runner/Create Own Runner instance
- AWS EC2

---

## Features

- Real-time currency conversion
- Docker containerization
- Automated CI/CD pipeline
- Docker Hub integration
- Deployment using Docker Compose

---

## CI/CD Workflow

1. Build Docker Image
2. Run Test Stage
3. Push Image to Docker Hub
4. Deploy on EC2 using Docker Compose

---

## Pipeline Screenshot

![alt text](screenshots/pipeline-success.png)

## Docker Commands Used

docker build -t currency-converter-app:latest .
docker-compose up -d

---

## Project Highlights:

* End-to-end CI/CD implementation
* Self-hosted GitLab Runner setup
* Dockerized deployment workflow
* AWS EC2 cloud deployment
* Automated Docker image management
* Linux server configuration
* CI/CD troubleshooting and debugging

---

## Future Improvements:

* Kubernetes deployment
* HTTPS setup
* Nginx reverse proxy
* Monitoring with Prometheus/Grafana

---

## Conclusion:

This project demonstrates practical DevOps skills including CI/CD automation, containerization, cloud deployment, GitLab Runner configuration, and Docker-based application deployment using AWS EC2.