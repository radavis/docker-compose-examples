# psql

```bash
$ dc up
$ sudo ss -tlnp sport = :5432 # or
$ sudo lsof -nP -iTCP:5432 -sTCP:LISTEN
# sudo apt install postgresql-client # if necessary
$ psql postgres://postgres:your-password-here@localhost:5432
postgres=# \h
postgres=# \q
```

- [hub.docker.com/postgres](https://hub.docker.com/_/postgres/#-via-docker-compose)