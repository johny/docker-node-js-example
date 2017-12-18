# Dockerized sample Node.js app with Express

This repo contains only sample Express app setup and Dockerfile.

## Building image

```
docker build -t <your username>/node-web-app .
```

## Running app

```
docker run -p 49160:8080 -d <your username>/node-web-app
```

