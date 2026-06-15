# AWS CI/CD Portfolio Deployment

## Overview

This project demonstrates a simple CI/CD pipeline using **GitHub Actions**, **Docker**, and **AWS EC2**.

Whenever code is pushed to the `main` branch, GitHub Actions automatically deploys the latest version of the application to an AWS EC2 instance.

## Tech Stack

* AWS EC2 (Ubuntu 24.04)
* Docker
* GitHub Actions
* Nginx
* SSH

## Deployment Flow

GitHub Push → GitHub Actions → EC2 Server → Docker Build → Container Deployment

## Features

* Automated deployment on every push to `main`
* Dockerized application
* Secure SSH-based deployment
* AWS-hosted application
* Zero manual deployment steps

## Project Structure

```text
.
├── Dockerfile
├── index.html
└── .github
    └── workflows
        └── deploy.yml
```

## Application URL
http://16.16.67.216

http://16.16.67.216

