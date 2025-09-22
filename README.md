# Shell-scripted-django

This project automates the deployment of a Django application on an AWS EC2 Ubuntu instance using Bash scripting, Docker, and Docker Compose. It handles cloning the code, installing dependencies, configuring services, and running the app in containers, making deployment fast, reliable, and fully automated.

## Features

- Automated code cloning from GitHub
- Dependency installation including Docker, Docker Compose, and Nginx
- Dockerized Django app for consistent environments
- Error handling at every step to ensure smooth deployment
- Optional notifications for deployment failures

## Technologies Used

- **Bash / Shell Scripting** – for automation  
- **Docker & Docker Compose** – for containerization  
- **AWS EC2 (Ubuntu AMI)** – cloud server deployment  
- **Nginx** – web server for serving the app  
- **Git** – for source code management  

## Usage

1. Clone this repository to your server:

   ```bash
   git clone https://github.com/YourUsername/django-bash-deploy.git

2. Make the deployment script executable:
   
   ```bash
   chmod +x django-app.sh

3. Run the script to deploy the Django app:

    ```bash
    ./django-app.sh

## Deployment Flow

- Clone Django app code
- Install required dependencies
- Perform necessary restarts and configuration
- Build and run Docker containers
- App deployed and running on the server

### This project is ideal for DevOps enthusiasts, backend developers, and anyone looking to automate Django app deployment on AWS using shell scripting.
