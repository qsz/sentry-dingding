# Sentry-tr-DingDing

`Sentry`的`钉钉`通知插件, 基于docker部署的Sentry（forked from anshengme/sentry-dingding ）

## 安装

```
$ vim Dockerfile，加上 RUN pip install git+https://github.com/qsz/sentry-dingding.git
$ docker-compose build --no-cache
$ docker-compose build --no-cache
$ docker-compose up -d
```

## 使用

在`项目`的所有集成页面找到`DingDing`插件，启用，并设置`Access Token`

![plugin](https://github.com/qsz/sentry-dingding/blob/master/docs/images/options.png)

