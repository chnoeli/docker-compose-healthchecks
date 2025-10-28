# Docker Compose Healthchecks
> Collection of Docker Compose healthcheck examples.

## Collection   

### Traefik

Important the `/ping` health-check URL needs to be enabled with the command-line `--ping` or config file option `[ping]`.

```yml
healthcheck:
  test: ['CMD', 'traefik', 'healthcheck', '--ping']
```

Sources: [[1]](https://doc.traefik.io/traefik/reference/install-configuration/observability/healthcheck/)

## Related

- [rodrigobdz/docker-compose-healthchecks q](https://github.com/rodrigobdz/docker-compose-healthchecks)