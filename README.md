# unifi-compose

Copy either `docker-compose.bind.yml` or `docker-compose.volume.yml` to `docker-compose.yml` depending on your preferred choice of volume type.

If you'd like to use a network volume for backups, see `network-volume.yml` for some syntax examples for NFSv3, NFSv4, and SMB/CIFS.

run:

```
docker compose config
```

to validate your config, then

```
docker compose up -d && docker compose logs -f
```

to fire it all up and watch the logs as it goes.

GLHF!
