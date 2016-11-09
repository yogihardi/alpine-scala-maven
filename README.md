[![Docker Stars](https://img.shields.io/docker/stars/yogihardi/alpine-scala-maven.svg?style=flat-square)](https://hub.docker.com/r/yogihardi/alpine-scala-maven/)
[![Docker Pulls](https://img.shields.io/docker/pulls/yogihardi/alpine-scala-maven.svg?style=flat-square)](https://hub.docker.com/r/yogihardi/alpine-scala-maven/)


Scala & Maven Docker image
==================

This image is based on Alpine Linux image, which is only a 5MB image, and contains
[Scala](http://www.scala-lang.org/) based on Oracle JDK 7
[`yogihardi/alpine-oraclejdk7` image](https://hub.docker.com/r/yogihardi/alpine-oraclejdk7/).


Usage Example
-------------

```bash
$ docker run --rm yogihardi/alpine-scala-maven scala -e 'object HelloWorld extends App { println("Hello World") }; HelloWorld.main(null)'
```

Once you have run this command you will get printed 'Hello World' from Scala!
