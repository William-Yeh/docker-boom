Docker-Boom
============

[![Build Status](https://travis-ci.org/William-Yeh/docker-boom.svg?branch=master)](https://travis-ci.org/William-Yeh/docker-boom)


## Summary

Repository name in Docker Hub: **[williamyeh/boom](https://hub.docker.com/r/williamyeh/boom/)**

This repository contains Dockerized [boom](https://github.com/rakyll/boom), published to the public [Docker Hub](https://hub.docker.com/) via **automated build** mechanism.



## Configuration

This docker image contains the following software stack:

- Alpine 3

- Boom

Total image size is less than 20 MB.


### Dependencies

- [`williamyeh/ansible:mini-alpine3`](https://hub.docker.com/r/williamyeh/ansible/).


### History

- 1.0 - Initial release.


## Installation

```
$ docker pull williamyeh/boom
```


## Usage


#### Show usage

```
$ docker run --rm williamyeh/boom
```


#### Typical example

```
$ docker run --rm  williamyeh/boom  \
      -n 1000 -c 100 https://google.com
```
