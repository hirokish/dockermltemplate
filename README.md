# Docker ML Template

This repository is to create an instant ML development environment empowered by Docker.

## Prerequisite

- Docker (v20.10.13 or later)
  - Assuming Docker Compose v2.

## How to use

1. Build the container using Compose.

```bash
$ docker compose build
```

2. Run the container.

```bash
$ docker compose build
```

3. Check the running container ID.

```bash
$ docker ps -a
CONTAINER ID   IMAGE                     COMMAND                  CREATED         STATUS                     PORTS     NAMES
281374e0ab1e   dockermltemplate_ml_dev   "python3"                8 minutes ago   Up 8 minutes                         dockermltemplate-ml_dev-1
```

4. Log-in to the container.

```bash
$ docker exec -it <the_container_id> /bin/bash
```
