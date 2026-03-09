# Docker Nginx Deploy Demo

A simple Python web app deployment example using Flask, Docker, Docker Compose, and Nginx as a reverse proxy.

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Docker](https://img.shields.io/badge/Docker-Containerized-blue)
![Nginx](https://img.shields.io/badge/Nginx-Reverse%20Proxy-green)

## What this project does

This repository demonstrates a minimal deployment setup where:

- a Flask app runs inside a Docker container
- Gunicorn serves the Python app
- Nginx acts as a reverse proxy
- Docker Compose orchestrates the services

## Project Structure

```text
docker-nginx-deploy-demo/
├── app/
│   ├── app.py
│   └── requirements.txt
├── nginx/
│   └── default.conf
├── Dockerfile
├── docker-compose.yml
├── .gitignore
├── README.md
└── screenshots/
    └── deploy-demo.png
