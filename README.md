# docker-compose-examples

`docker-compose` examples for running services in a local development environment.

```bash
$ docker ps
$ cd service-name
$ cp .env.example .env # then, modify vars
$ alias dc=docker-compose
$ dc up -d # then, use the service
$ dc logs -f
$ dc exec service sh # drop into conatiner shell
$ dc down
```
