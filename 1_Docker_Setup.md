# Docker Setup

## First service with Dockerfile
- Create admin service
- Build the image with `docker build -t ffk-service-admin .`
- Now the Docker instance appears as an image on `docker images`
```bash
REPOSITORY          TAG                 IMAGE ID            CREATED             SIZE
ffk-service-admin   latest              7b89dc5aa956        3 minutes ago       1.29GB
```
- Run the container with `docker run -d -p 5000:5000 ffk-service-admin`

## Dockerhub
- Create an account on Dockerhub
