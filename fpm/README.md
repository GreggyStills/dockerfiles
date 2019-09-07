
## fpm Dockerfile

This repository contains **Dockerfile** of the nifty package-building utility, [fpm](https://fpm.readthedocs.io)


### Installation

1. Install [Docker](https://www.docker.com/).

2. Build an image from this Dockerfile: `docker build -t fpm .`


### Usage
```
    docker run --rm fpm <flags>
```

Tip: create a command alias!
```
    alias fpm='docker run --rm fpm'

Example:
laptop:~ > fpm -h
Intro:

  This is fpm version 1.11.0
...snip
```   

