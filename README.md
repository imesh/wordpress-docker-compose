# Wordpress Docker Compose with MySQL

This Docker Compose template includes latest wordpress Docker image and MySQL 5.7 image including volume mounts for preserving MySQL data directory and Wordpress content directory.

## How to Run

- Clone this git repository and switch to the root folder.

- Execute Docker Compose Up command to start the containers:
  ````bash
  docker-compose up
  ````

- Open a web browser and visit the following URL:

  ````
  http://localhost:8000/
  ````

## License
Licensed under Apache 2.0