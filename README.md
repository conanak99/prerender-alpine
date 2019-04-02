# Prerender Alpine

Lightweight Prerender container built on Alpine Linux with Node and Headless Chrome. 

Folked from [tvanro/prerender-alpine](https://hub.docker.com/r/tvanro/prerender-alpine)

- Prerender 5.6.0
- Chromium 72.0.3626.121-r0
- Node 10.15.3

## Requirements

- Docker

## Usage

Pull and run the image:

```
docker pull conanak99/90seconds-prerender:1.0.0
docker run -p 3000:3000 conanak99/90seconds-prerender:1.0.0
```
Prerender will now be running on http://localhost:3000. Try the container out with curl:

```
curl http://localhost:3000/render?url=https://www.example.com/
```

Check out the official Prerender documentation: https://github.com/prerender/prerender
