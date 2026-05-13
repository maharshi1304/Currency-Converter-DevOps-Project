# Currency Converter DevOps Architecture

## Project Overview

This project demonstrates a complete CI/CD deployment workflow for a Dockerized Currency Converter web application using GitLab CI/CD, Docker, Docker Hub, and AWS EC2 with a self-hosted GitLab Runner.

The objective of this project is to automate:
- application build
- testing
- Docker image creation
- Docker Hub image push
- deployment workflow


# Architecture Flow

Developer (MacBook)
        │
        │ Git Push
        ▼
GitLab Repository
        │
        │ Triggers Pipeline
        ▼
GitLab CI/CD Pipeline
        │
        ├── Build Stage
        │       └── Docker image build
        │
        ├── Test Stage
        │       └── Basic application testing
        │
        ├── Push Stage
        │       └── Push Docker image to Docker Hub
        │
        └── Deploy Stage
                └── Docker Compose deployment on EC2
                        │
                        ▼
                AWS EC2 Instance
                        │
                        ├── Docker Engine
                        ├── Docker Compose
                        └── Self-Hosted GitLab Runner
                                │
                                ▼
                        Running Containerized Application