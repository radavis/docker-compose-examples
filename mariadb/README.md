# mariadb

```bash
$ dc up
$ sudo ss -tlnp sport = :3306 # or
$ sudo lsof -nP -iTCP:3306 -sTCP:LISTEN
# sudo apt install mariadb-client # if necessary
$ mariadb --protocol=TCP --host=localhost --port=3306 --user=root --password=your-password-here
MariaDB> \h
MariaDB> \q
```

- [hub.docker.com/mariadb](https://hub.docker.com/_/mariadb#-via-docker-compose)
