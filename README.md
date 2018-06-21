# HOME PROXY WITH TRAEFIK

You need to create file acme.json

```bash
touch acme.json && chmod 600 acme.json
````

You need to create the network first

```bash
docker network create traefik_default
```

And after:

```bash
docker-compose up
```