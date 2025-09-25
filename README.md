# Docker + Nginx + PHP + MySQL + PhpMyAdmin

## Configuration

Edit the `.env.example` file.

## Installation

Open a terminal and `cd` to the folder in which `docker-compose.yml` is saved and run:

```
docker compose up -d
```

### Stopping containers

```
docker compose stop
```

### Removing containers

To stop and remove all the containers use the `down` command:

```
docker compose down
```

Use `-v` if you need to remove the database volume which is used to persist the database:

```
docker compose down -v
```
