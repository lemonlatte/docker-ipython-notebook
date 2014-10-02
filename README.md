## ipython notebook Dockerfile

This repository contains **Dockerfile** of [ipython-notebook](http://ipython.org/notebook.html). Scipy and Pandas are bundled in this container.

### Installation

1. Install [Docker](https://www.docker.com/).

2. Pull the image from Docker Hub

```
$ docker pull lemonlatte/docker-ipython-notebook
```

### Usage

```
$ docker run -d -p 8888:8888 -v /path/to/workspace:/ipython-notebook/workspace lemonlatte/docker-ipython-notebook
```

