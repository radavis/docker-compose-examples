# nginx

## host static content

```bash
# with docker
$ docker run \
    --name my-nginx \
    --volume /some/content:/usr/share/nginx/html:ro \
    --detach \
    nginx

# with docker-compose
$ alias dc=docker-compose
$ dc up -d
```

Visit [localhost:8080]
