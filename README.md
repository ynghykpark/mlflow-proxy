# aloohai-webservices

## How to run
First, create .htpasswd files for basic authentication.

```bash
htpasswd -c .htpasswd username
```

Second, edit .env to configure your own environment.

Finally, run containers.

```bash
docker-compose up -d
```
