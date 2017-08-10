# hitse/pipelines

This repository contains the source of [hitse/pipelines](https://hub.docker.com/r/hitse/pipelines)

At the moment I manually build and push the docker image to docker hub.

## How to build and push image

```
docker build -t pipelines:latest .
```

```
docker tag pipelines hitse/pipelines
```

see https://docs.docker.com/docker-cloud/builds/push-images/
