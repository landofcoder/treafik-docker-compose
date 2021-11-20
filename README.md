# Sample Local Traefik reverse proxy for development

This docker compose use latest version of traefik

## Installation
- Change there certs files with your domain key files in folder: configuration/certs/
- Run command:
```
docker-compose up -d
```

## Monitoring
- access url on browser: http://proxy.monitor.localhost or http://localhost:8080
- access whois: http://whoami.localhost


More inforamtion, please visit: https://doc.traefik.io/traefik/user-guides/docker-compose/basic-example/