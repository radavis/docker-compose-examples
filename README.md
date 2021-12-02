# docker-compose-examples

`docker-compose` examples for running services in a local development environment.

```bash
$ cd service-name
$ cp .env.example .env # then, modify vars
$ alias dc=docker-compose
$ dc up -d # then, use the service
$ dc logs -f
$ dc down
```
