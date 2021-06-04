# PBOT Public Involvement Planning
This repository contains the codebase of a Drupal-based content management system (CMS). The site is intended to help PBOT employess collaborate on public involvement internally.

## Developer guide
This repository leverages [Docker](//docker.com) to speed development time. This section will focus on getting a new developer up and running on a machine with Docker and Docker Compose installed already. For the following sections you should have Docker running.
### Building images
You'll first need to build the local images to run the docker services. You can do that by running the following command:
```bash
docker-compose build
```
This will build any images defined as building from Dockerfiles in the `docker-compose.yml` file.
### Starting services
