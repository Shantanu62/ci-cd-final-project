# CI/CD Tools and Practices Final Project — JavaScript/Node.js

Project: **Counter Service CI/CD Pipeline**

This repository contains the JavaScript/Node.js Express Counter Service final project for the IBM/Coursera CI/CD Tools and Practices course.

## CI/CD Implementation

- GitHub Actions workflow: `.github/workflows/workflow.yml`
- ESLint lint checks and Jest unit tests
- Tekton cleanup and Jest-test tasks: `.tekton/tasks.yml`
- OpenShift deployment pipeline evidence to be added after successful execution

## Application

Node.js / Express counter service. The starter project includes REST endpoints for creating, listing, reading, incrementing, and deleting counters, along with a health check endpoint.

## Local Commands

```bash
npm ci
npm run lint
npm test -- --runInBand
npm start
```

## Project Repository

https://github.com/Shantanu62/ci-cd-final-project
