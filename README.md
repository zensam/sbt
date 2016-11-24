## Scala and sbt Dockerfile

**Dockerfile** for Jenkins slave with [Scala](http://www.scala-lang.org) and [sbt](http://www.scala-sbt.org).


### Base Docker Image

* [openjdk:8](https://hub.docker.com/r/_/openjdk/)


### Installation

1. Install [Docker](https://www.docker.com)
2. Pull [automated build](https://hub.docker.com/r/zensam/sbt/) from Docker Hub Registry:
```
docker pull zensam/sbt
```
Alternatively, you can build an image from Dockerfile:
```
docker build -t zensam/sbt github.com/zensam/sbt
```


### Usage

```
docker run -it --rm zensam/sbt
```
