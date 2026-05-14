# CI/CD Pipeline Project 

This project is a simple Node.js application with a CI/CD pipeline using GitHub Actions and Docker.

## Features
- Node.js + Express web server
- Automated CI pipeline using GitHub Actions
- Docker containerization
- Automatic build and test on every push

## CI/CD Flow
Push code → GitHub Actions runs → Install dependencies → Run tests → Build Docker image

## How to run locally
npm install
npm start

## Docker
docker build -t cicd-app .
docker run -p 3000:3000 cicd-app
