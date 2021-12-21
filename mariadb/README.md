# mariadb

```bash
$ cp .env.example .env # then modify
$ alias dc=docker-compose
$ dc up -d
$ mysql --protocol=TCP --host=localhost --port="$PORT" --user=root --password="$MYSQL_ROOT_PASSWORD"
$ dc down
```
