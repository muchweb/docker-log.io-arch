# What is "log.io"?

Log.io is Real-time log monitoring in your browser. Read more here: (http://logio.org/)[http://logio.org/].

# How to use this image

## Running

```bash
docker run -d -p 28777:28777 -p 28778:28778 'muchweb/log.io-arch'
```

This image includes:

- `EXPOSE 28777` — log listening port
- `EXPOSE 28778` — web admin server port
