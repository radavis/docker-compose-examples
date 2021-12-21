# notes

## cli

```bash
$ nginx -s {stop,quit,reload,open}
```

## serve static content

```conf
http {
  server {
    # serve files at '/data/www' from '/'
    location / {
      root /data/www;
    }

    # serve files at '/data/images' from '/images'
    location /images/ {
      root /data;
    }
  }
}
```
