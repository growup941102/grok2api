# GitHub Actions
此项目使用 GitHub Actions 自动构建 Docker 镜像。

## 构建状态

[![Docker](https://github.com/tanranv5/grok2api/actions/workflows/docker.yml/badge.svg)]

## 使用方法

```bash
docker pull ghcr.io/tanranv5/grok2api:latest
docker run -d -p 8000:8000 ghcr.io/tanranv5/grok2api:latest
```
