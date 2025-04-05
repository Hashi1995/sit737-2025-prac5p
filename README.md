# sit737-2025-prac5p - Containerisation of a simple web application using Docker
This project includes a simple web application with Docker. Also include the building a Docker image and deploying the container using Docker Compose. It also include the container health check mechanism.

# Required Software
Git (https://github.com)
Visual Studio code (https://code.visualstudio.com/)
Node.js (https://nodejs.org/en/download/)
Docker

# Instructions
•	First, I have created “sit323_737-2023-t1-prac5p” project folder using “npm init-y”.
•	Next, I have installed express using “npm install express”
•	Then, I have created simpleserver.js file
•	After that I have created Docker file
•	Next, I have created docker-compose.yml file
•	Now, have run the server using “http://localhost:3000” using terminal “node simpleserver.js”
•	Now, I build the docker image using terminal type “docker build -t hashinig/simpleserver .”
•	Then run the image “docker run -p 8080:3000 hashinig/simpleserver”
•	Now type “docker images” – you can see your image
•	Now I create docker compose – “docker compose up”
•	Now check the docker desktop and test the application

For the helth check,
•	In here I added “health check code” to the docker-compose.file.
•	Next I have rebuild the docker image and check the system is health or not using “docker-compose ps”.
