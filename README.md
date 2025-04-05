Dockerising a Node.js Web Application

This practical demonstrates how to:
- Containerise a simple Node.js application using Docker.
create dockerfile
create docker-compose.yml file

Add a health check to the container.
health check
docker ps

Push the Docker image to Docker Hub

docker tag simple-node-app Raghavanaveen/sit737-2025-prac5p

docker push Raghavanaveen/sit737-2025-prac5p

Setting Up the GitHub Repository

Initialized Git in the project directory:
git init

git remote add origin https://github.com/Raghavanaveen/sit737-2025-prac5p.git

git add .

git commit -m "Initial commit "

git push -u origin main
