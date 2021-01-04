# Docker Cheat Sheet

## Run container

```bash
docker run hello-world
```

> Your container is now running

## Watch all container

```bash
docker ps --all
```

### Return

| CONTAINER ID | IMAGE       | COMMAND  | CREATED        | STATUS                    | PORTS | NAMES              |
| ------------ | ----------- | -------- | -------------- | ------------------------- | ----- | ------------------ |
| 88c6441cf6db | ubuntu      | "bash"   | 14 minutes ago | up 12 minutes             |       | hardcore_engelbart |
| d3725d653878 | hello-world | "/hello" | 20 minutes ago | Exited (0) 19 minutes ago |       | serene_dewdney     |

## Stop Container

> Close ubuntu container

```bash
docker stop hardcore_engelbart
```

## Delete container

> Before deleting you need to stop the container

```bash
docker rm hardcore_engelbart
```

## List Images

```bash
docker images -a
```

## Delete images

```bash
docker rmi ubuntu
```

## Delete all unused ressources ... ( images, containers, network )

```bash
docker system prune
```
