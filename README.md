# docker-immich
Docker setup for running Immich behind a Traefik instance

## Docker Setup
1. Initialize config by running init.sh: `./init.sh`
1. Input personal information into `.env`
1. Make sure that Docker network `traefik` exists, `docker network ls`
1. Run `docker compose up` and check logs.

## Authentik/Immich setup
See relevant [Authentik](https://github.com/znibb/docker-authentik#45-immich) repo