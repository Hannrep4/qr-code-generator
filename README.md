# QR Code Generator

DockerHub image:
https://hub.docker.com/r/hannrep/qr-code-generator-app

## Pull the image

```bash
docker pull hannrep/qr-code-generator-app:latest
```

## Run the container

```bash
docker run --rm -v %CD%/qr_codes:/app/qr_codes hannrep/qr-code-generator-app:latest
```
