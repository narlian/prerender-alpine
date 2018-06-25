# Prerender Alpine

Lightweight Prerender container built on Alpine Linux with Node and Headless Chrome.

- Prerender 5.4.2
- Chromium 64.0.3282.168-r0
- Node 10.3.0

## Requirements

- Docker

## Usage

Pull and run the image:

```
docker pull tvanro/prerender-alpine:5.4.2
docker run -p 3000:3000 tvanro/prerender-alpine:5.4.2
```
Prerender will now be running on http://localhost:3000. Try the container out with curl:

```
curl http://localhost:3000/render?url=https://www.example.com/
```

See the complete Prerender documentation for additional information: https://github.com/prerender/prerender