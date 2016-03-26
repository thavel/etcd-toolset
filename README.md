# etcd-toolset

[![Docker Pulls](https://img.shields.io/docker/pulls/thavel/etcd-toolset.svg)](https://hub.docker.com/r/thavel/etcd-toolset)
[![Image Size](https://img.shields.io/imagelayers/image-size/thavel/etcd-toolset/latest.svg)](https://imagelayers.io/?images=thavel/etcd-toolset:latest)
[![Image Layers](https://img.shields.io/imagelayers/layers/thavel/etcd-toolset/latest.svg)](https://imagelayers.io/?images=thavel/etcd-toolset:latest)

Lightweight Docker image based on Alpine 3.3 embedding [etcd](https://github.com/coreos/etcd) toolset.

* [confd](https://github.com/kelseyhightower/confd)
* [editd](https://github.com/thavel/editd)

## Getting started

Download the image from [Dockerhub](https://hub.docker.com/r/thavel/etcd-toolset):

```bash
docker pull thavel/etcd-toolset
```

### Basic usage example

```bash
docker run --rm thavel/etcd-toolset /usr/local/bin/confd -h
docker run --rm thavel/etcd-toolset /usr/local/bin/editd -h
```
