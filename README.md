# Docker Node

A modified docker node image based on official [node:alpine](https://hub.docker.com/_/node/).

*Note: Size of this image is large, **~300M**. Personally I only use it when installing npm packages. Some kind of like this,*

```
$ docker run --rm -v $(pwd):/app -w /app milespeng/node:alpine npm install
```

## Supported Tags

- [`alpine`](https://github.com/MilesPong/docker-node/blob/master/Dockerfile)

## Changed

- Have [cnpm](https://github.com/cnpm/cnpm) installed
- With some build dependencies installed

## Installed Build Dependencies

- libpng-dev
- autoconf
- automake
- make
- g++
- libtool
- nasm
