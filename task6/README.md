# TASK6

> [Repository overview](../README.md) · [Parent module](../README.md)

**Module:** `task6` · **Repository:** `holbertonschool-softy-pinko-docker`

Extend the architecture to multiple backend instances and load distribution.

## Subdirectories

| Directory | Focus |
| --- | --- |
| [`back-end/`](./back-end/) | Python/Flask backend application and its container configuration. |
| [`front-end/`](./front-end/) | Frontend application and its container configuration. |
| [`proxy/`](./proxy/) | Nginx proxy configuration and its Docker image. |

## Exercises and files

| File | Description |
| --- | --- |
| [`2-api-servers.txt`](./2-api-servers.txt) | Exercise 2 — Api servers. |
| [`docker-compose.yml`](./docker-compose.yml) | Multi-service Docker Compose configuration. |

## Development notes

The Compose file describes how this task coordinates multiple containers. Review its service paths and ports before running `docker compose up --build`.

## Attribution

Coursework repository maintained by [RohMeOh](https://github.com/RohMeOh). This page indexes the tracked files; authorship and contributions are documented in Git history. Images, fonts and vendor files, where present, may be third-party assets.
