AWS DevOps CI/CD Pipeline

Project Overview

This project demonstrates a simple Continuous Integration and Continuous Deployment (CI/CD) pipeline using AWS EC2, Jenkins, Docker, Git, and GitHub.

The application is hosted on an AWS EC2 instance. Jenkins automates the build process by pulling the latest code from GitHub, building a Docker image, and deploying the application inside a Docker container.

#Technologies Used

- Amazon Web Services (AWS EC2)
- Jenkins
- Docker
- Git
- GitHub
- HTML
- CSS
- Nginx

#Project Structure


aws-devops-cicd-pipeline/
│── Dockerfile
│── Jenkinsfile
│── index.html
│── style.css
│── README.md

#CI/CD Workflow

1. Developer pushes code to GitHub.
2. Jenkins pulls the latest code from the GitHub repository.
3. Jenkins executes the Jenkins Pipeline.
4. Docker builds the application image.
5. Docker creates and runs the container.
6. The application is deployed successfully on the AWS EC2 instance.

#Docker Commands Used

Build Docker Image

docker build -t my-web-app .

#View Docker Images

docker images

#Run Docker Container

docker run -d -p 80:80 --name my-container my-web-app

#View Running Containers

docker ps

#Project Screenshots

The project includes the following screenshots:

- AWS EC2 Instance
- Jenkins Dashboard
- Jenkins Successful Build
- GitHub Repository
- Docker Images
- Docker Running Container
- EC2 Terminal
- Web Application Output

#Application Output

The application displays:

AWS DevOps CI/CD Pipeline

This application is deployed using:

Git & GitHub
Jenkins
Docker
Amazon EC2

Deployment Successful

#Learning Outcomes

Through this project, I learned:

- Setting up an AWS EC2 instance
- Installing and configuring Jenkins
- Creating a Jenkins Pipeline
- Building Docker images
- Running Docker containers
- Hosting applications using Docker
- Integrating GitHub with Jenkins
- Implementing a basic CI/CD pipeline

Features

- Automated Build Process
- Dockerized Web Application
- Jenkins Pipeline Integration
- GitHub Source Code Management
- AWS Cloud Deployment

#Project Status

Project Completed Successfully
