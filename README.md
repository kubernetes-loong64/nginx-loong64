# Nginx for LoongArch (loong64)

<p align="center"><a href="README.md">English</a> | <a href="README-zh.md">中文</a></p>

Nginx Docker container images ported to the **LoongArch (loong64)** architecture.

This repository builds and publishes Nginx container images for LoongArch by applying minimal patches to the upstream
[nginx/docker-nginx](https://github.com/nginx/docker-nginx) to support alternative base images.

## Docker Images

Images are published to Docker Hub under
[`kubernetesloong64/nginx-loong64`](https://hub.docker.com/r/kubernetesloong64/nginx-loong64).

- [![kubernetesloong64/nginx-loong64](https://img.shields.io/docker/v/kubernetesloong64/nginx-loong64?arch=loong64&logo=docker&label=kubernetesloong64%2Fnginx-loong64&sort=semver)](https://hub.docker.com/r/kubernetesloong64/nginx-loong64/tags)

Two base image variants are provided per version:

- **debian** — based on `lcr.loongnix.cn/debian:14`
- **debian-slim** — based on `lcr.loongnix.cn/debian:14-slim`

### Pull Images

```shell
docker pull kubernetesloong64/nginx-loong64:1.31.2-debian-slim
```

## License

[Apache License 2.0](LICENSE)
