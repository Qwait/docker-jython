# Supported tags and respective `Dockerfile` links
- [`2.7.0`, `latest` (*2.7.0/Dockerfile*)](https://raw.githubusercontent.com/Qwait/docker-jython/master/2.7.0/Dockerfile)

[![](https://badge.imagelayers.io/qwait/docker-jython:latest.svg)](https://imagelayers.io/?images=qwait/docker-jython:latest)

# How to use this image

## Run a single script
```console
$ docker run -it --rm -v "$PWD":/usr/src/myapp -w /usr/src/myapp qwait/docker-jython jython script.py
```
