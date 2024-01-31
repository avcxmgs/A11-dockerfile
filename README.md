## Coding Assignment 11

WEBD-3012 (249570) Business Systems Build and Testing
Name: Margareth Santos

1. Create empty folder and clone repo from GitHub using:
git clone git@github.com:avcxmgs/A11-dockerfile.git

2. Navigate to the folder:
cd A11-dockerfile

3. Start Docker Desktop

4. Build and tag the Docker image:
docker build -t coding_assignment_11:dev .

5. Build the image and start the container:
docker-compose up -d --build

6. Check on a browser that the web application is running:
http://localhost:7775/

7. Stop the container:
docker-compose stop