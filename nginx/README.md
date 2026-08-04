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
$ dc up -d
$ curl localhost:8080
$ open http://localhost:8080
```

- [hub.docker.com/nginx](https://hub.docker.com/_/nginx#how-to-use-this-image)
