# Docker Debian

[![Build Status](https://travis-ci.org/ckaserer/docker-debian.svg?branch=master)](https://travis-ci.org/ckaserer/docker-debian)
[![This image on DockerHub](https://img.shields.io/docker/pulls/ckaserer/debian.svg)](https://hub.docker.com/r/ckaserer/debian/)

[![](https://images.microbadger.com/badges/version/ckaserer/debian.svg)](https://microbadger.com/images/ckaserer/debian "Get your own version badge on microbadger.com")
[![](https://images.microbadger.com/badges/image/ckaserer/debian.svg)](https://microbadger.com/images/ckaserer/debian "Get your own image badge on microbadger.com")

The images can run on both on x86/x64 and ARM systems. The build is automated and new images are pushed to Docker Hub every week.

Hypriot done a wonderful job in detailing how to create Docker images that can run on both on x86/x64 and ARM systems ([Setup a simple CI pipeline to build Docker images for ARM](https://blog.hypriot.com/post/setup-simple-ci-pipeline-for-arm-images/)).

On that foundation I have build a travis job that would create debian images for

* experimental
* jessie
* 8.10
* 8
* jessie-backports
* jessie-slim
* 8.10-slim
* 8-slim
* stable
* stable-backports
* stable-slim
* stretch
* 9.4
* 9
* latest
* stretch-backports
* stretch-slim
* 9.4-slim
* 9-slim
* wheezy
* 7.11
* 7
* wheezy-backports
* wheezy-slim
* 7.11-slim
* 7-slim