## Dockerfile

This is a repository for my personal dockerfiles.

This repository contains **Dockerfile** of [Java](https://www.java.com/) for [Docker](https://www.docker.com/)'s [automated build](https://registry.hub.docker.com/u/dockerfile/java/) published to the public [Docker Hub Registry](https://registry.hub.docker.com/).


### Base Docker Image

* [dockerfile/ubuntu](http://dockerfile.github.io/#/ubuntu)


### Docker Images/Tags

* `ubuntu:latest`: Ubuntu Wily (LTS)
* `openjdk:6-jdk`: OpenJDK Java 6 JDK
* `openjdk:6-jre`: OpenJDK Java 6 JRE
* `openjdk:7-jdk`: OpenJDK Java 7 JDK
* `openjdk:7-jre`: OpenJDK Java 7 JRE
* `openjdk:8-jdk`: OpenJDK Java 8 JDK
* `openjdk:8-jre`: OpenJDK Java 8 JRE
* `openjdk:9-jdk`: OpenJDK Java 9 JDK
* `openjdk:-9-jre`: OpenJDK Java 9 JRE
* `java:6`: Oracle Java 6 JDK
* `java:7`: Oracle Java 7 JDK
* `java:8`: Oracle Java 8 JDK
* `java:9`: Oracle Java 9 JDK
* `oracle-java-base:latest` : Oracle Java
* `wildfly-servlet:10.1.0.Final` : Wildfly 10 Web Profile


### Installation

1. Install [Docker](https://www.docker.com/).

2. Install [autoenv](https://github.com/kennethreitz/autoenv)

3. (Optional) Use dbuild command to build Oracle Java base image, if you want to build Oracle Java images

    dbuild oracle-java-base

4. Build any image locally with dbuild command

	dbuild ubuntu

