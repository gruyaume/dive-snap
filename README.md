# Dive snap
[![dive](https://snapcraft.io/dive/badge.svg)](https://snapcraft.io/dive)

A snap to run [Dive](https://github.com/wagoodman/dive), a tool for exploring a docker image.

## Usage

Install the Docker and Dive snaps and connect them:

```console
sudo snap install docker
sudo snap install dive
sudo snap connect dive:docker-executables docker:docker-executables
sudo snap connect dive:docker-daemon docker:docker-daemon
```

Run `dive`:

```console
dive ubuntu:latest
```
