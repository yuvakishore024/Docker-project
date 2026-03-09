# Dockerized Application Deployment

This project demonstrates how to containerize and run an application using **Docker**.  
The goal of this project is to package the application and its dependencies into a Docker container so that it can run consistently across different environments without configuration issues.

The repository includes a **Dockerfile** that defines the steps required to build a Docker image. Once the image is built, a container can be created and executed to run the application in an isolated environment.

### Technologies Used
- Docker
- Dockerfile
- Linux
- Git
- GitHub

### How to Run the Project

Clone the repository

git clone https://github.com/yuvakishore024/Docker-project.git

Navigate to the project directory

cd Docker-project

Build the Docker image

docker build -t docker-project .

Run the Docker container

docker run -d -p 8080:8080 docker-project

After running the container, the application will be accessible on the mapped port.

### Learning Outcome

This project demonstrates the fundamentals of Docker including creating Docker images, running containers, and managing containerized applications.

### Author

Yuvakishore JV  
GitHub: https://github.com/yuvakishore024
