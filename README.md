InfotechSoft Maven/Java Images
========================

This repository contains `Dockerfiles` for running and building Java applications on CentOS within docker containers using Apache Maven.

## How to Use

### As build environment

```
docker run -it --rm --name mvn-build -v "$(pwd)":/tmp -w /tmp maven:3-jdk-11 mvn clean package
```
