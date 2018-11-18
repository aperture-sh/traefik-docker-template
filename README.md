# Marauder Traefik base config

1. Move `conf` folder to `/opt`
2. `chmod -R 600 /opt/traefik`
3. Make sure the file/dir owner/group are set correct
3. `docker-compose up -d`
4. Attach containers to `web` network
