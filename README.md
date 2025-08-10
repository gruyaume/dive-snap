# Dive snap
[![dive](https://snapcraft.io/dive/badge.svg)](https://snapcraft.io/dive)

> **:warning: Deprecation Notice!**
>
> This snap is deprecated and will not receive further updates. Please refer to the upstream [Dive](https://github.com/wagoodman/dive) project to continue using Dive.

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
