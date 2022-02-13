# A custom image and docker-compose files for running Jenkins on https

Creates a new image based on Jenkins with Docker installed and the proper docker group created.  Also adds the 'jenkins' user to the docker group.
Runs a Jenkins container with https.
It also enables Docker within the container.

## Running the container
To run, first build the image and then use docker compose up.
