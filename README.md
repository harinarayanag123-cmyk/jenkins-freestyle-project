# Jenkins CI/CD Pipeline

## Overview
This project demonstrates the implementation of a Continuous Integration and Continuous Deployment (CI/CD) pipeline using Jenkins. The pipeline automates the process of building, testing, and deploying a Java-based web application.

## Tech Stack
- Jenkins
- Apache Maven
- SonarQube
- Apache Tomcat
- AWS EC2

## Architecture Workflow
1. Source code is pushed to the repository.
2. Jenkins automatically triggers the pipeline.
3. Maven builds the application and generates artifacts.
4. Unit testing is executed.
5. SonarQube performs static code analysis.
6. Application is deployed to Apache Tomcat server.

## Key Features
- Automated CI/CD pipeline
- Integrated code quality analysis
- Reduced manual deployment effort
- Scalable cloud-based deployment

## Challenges
- Jenkins plugin configuration
- SonarQube integration setup
- Deployment troubleshooting on Tomcat

## Results
- Successful pipeline execution with automated deployment
- Improved build reliability and deployment speed

## Documentation
Refer to `project-report.pdf` for detailed implementation.
