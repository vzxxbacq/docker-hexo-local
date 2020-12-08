基于[Repo](https://github.com/zeusro/docker-hexo)修改

使用本地资源进行构建。

## 使用方法


### docker-compose

1. 修改 `docker-compose.yml` 里的 `environment`;
1. `docker-compose up --force-recreate --build`

### [docker](https://hub.docker.com/r/zeusro/hexo)

```bash
    docker run -p 4000:4000 zeusro/hexo:latest  \
    --env PUBLIC_HEXO_GITHUB_URL=https://github.com/zeusro/docker-hexo.git
```
