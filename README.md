# docker-challenge-template

# Docker Challenge 1 Report
- Student Name: Billy Chan
- Student ID: 000900591

## Introduction
This report details my experience and learning process during Challenge 1 of our Docker project. The goal was to understand the basics of Docker, build a Docker image, and run a container to serve static web pages using Nginx.


## Procedure
1. Environment Setup:
- Installed Docker Desktop on Windows.
- Forked the necessary GitHub repository and cloned it to my local machine.

2. Creating the Webpage:
- Created a public folder inside the challenge1 directory.
- Added an index.html file with my personal details.

3. Preparing the Docker Environment:
- Wrote a Dockerfile to pull the nginx:alpine image and copy the contents of my public folder into /usr/share/nginx/html in the container.

4. Building the Docker Image:
- Ran docker build -t webserver . in the terminal within the challenge1 directory to build my Docker image.

5. Running the Container:
- Started the container using docker run --name mywebserver -d -p 8080:80 webserver.
- Ensured that the website was accessible by visiting http://localhost:8080 in a web browser.

6. Version Control:
- Used Git commands to add, commit, and push the Dockerfile and public folder to my GitHub repository.


## Results
Successfully accessed the static webpage served by the Docker container. Below are screenshots illustrating the process:
![Webpage Served by Docker](challenge1/public/Screenshots/webpage_served_by_docker.png)
![Docker Commands Execution](challenge1/public/Screenshots/docker_commands_execution.png)
![Docker Desktop Interface](challenge1/public/Screenshots/docker_desktop_interface.png)


## Conclusion
This challenge provided a practical introduction to Docker, teaching me how to build an image, run a container, and serve static content using Nginx. I am looking forward to applying these skills in future projects and exploring more advanced Docker functionalities.