# docker image

**1. What is the purpose of the 'COPY ./index.html /var/www/html/index.html' command in the Dockerfile?**

- A) To download a web page from the internet
- B) To create a new directory for the web server
- C) To move custom web content into the image
- D) To delete the default Apache index file

**2. Which Dockerfile instruction is used to specify the command that runs when the container starts?**

- A) RUN
- B) FROM
- C) CMD
- D) EXPOSE

**3. Why is the '-D FOREGROUND' flag used when starting Apache in a Docker container?**

- A) To hide the output from the terminal
- B) To prevent the container from exiting immediately
- C) To speed up the installation process
- D) To enable encrypted HTTPS traffic

**4. What command is used to build a Docker image with the tag 'david-rocky-apache'?**

- A) docker run -t david-rocky-apache
- B) docker build -t david-rocky-apache .
- C) docker create -n david-rocky-apache
- D) docker push david-rocky-apache

**5. In the command 'docker run -d -p 80:80 david-rocky-apache', what does the '-d' flag represent?**

- A) Delete after run
- B) Debug mode
- C) Detached mode
- D) Directory path

**6. How does the presentation define Docker Compose?**

- A) A tool for editing Dockerfiles
- B) A tool for defining and running multi-container applications
- C) A cloud hosting service for images
- D) A security scanner for Rocky Linux

**7. Which file defines all the options for a multi-container Docker application?**

- A) docker.config
- B) index.html
- C) docker-compose.yml
- D) package.json

**8. What command is used to start the containers defined in a Docker Compose file?**

- A) docker compose start
- B) docker compose up -d
- C) docker compose run
- D) docker compose build

**9. What is the specific command used to shut down a Docker Compose application?**

- A) docker compose stop
- B) docker compose remove
- C) docker compose down
- D) docker compose exit

