# Nginx for LoongArch (loong64)

<p align="center"><a href="README.md">English</a> | <a href="README-zh.md">中文</a></p>

将 Nginx Docker 容器镜像移植到 **LoongArch (loong64)** 架构。

本仓库通过对上游 [nginx/docker-nginx](https://github.com/nginx/docker-nginx) 应用最小化补丁以支持替代基础镜像，从而构建并发布适用于 LoongArch 的 Nginx 容器镜像。

## Docker 镜像

镜像发布在 Docker Hub 上的
[`kubernetesloong64/nginx-loong64`](https://hub.docker.com/r/kubernetesloong64/nginx-loong64)。

- [![kubernetesloong64/nginx-loong64](https://img.shields.io/docker/v/kubernetesloong64/nginx-loong64?arch=loong64&logo=docker&label=kubernetesloong64%2Fnginx-loong64&sort=semver)](https://hub.docker.com/r/kubernetesloong64/nginx-loong64/tags)

每个版本提供两种基础镜像变体：

- **debian** — 基于 `lcr.loongnix.cn/debian:14`
- **debian-slim** — 基于 `lcr.loongnix.cn/debian:14-slim`

### 拉取镜像

```shell
docker pull kubernetesloong64/nginx-loong64:1.31.2-debian-slim
```

## 许可证

[Apache License 2.0](LICENSE)
