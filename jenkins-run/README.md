# Docker Compose file for running Jenkins on https

Runs a Jenkins container with https.
It also enables Docker within the container.

## Caveats
This method requires manual creation of docker group and adding the 'jenkins' user to that group.
Without this, the Jenkins container cannot issue docker commands.
