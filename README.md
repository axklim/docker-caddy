# docker-caddy
another one image of [caddy web server](https://github.com/mholt/caddy)

Local run, you see: 404 Not Found
```bash
docker run --rm -p 80:2015 \
    -v $(pwd)/Caddyfile:/Caddyfile \
    -v $(pwd)/caddy:/caddy gudik/caddy
```

Simple Caddyfile:
```
localhost {
}
```