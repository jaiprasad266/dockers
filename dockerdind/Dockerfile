FROM docker:dind

RUN apk update

RUN apk add openjdk8

ENV JAVA_HOME=/usr/lib/jvm/java-1.8-openjdk

ENV JAVA_VERSION=1.8.0_302

ENV PATH=${PATH}:${JAVA_HOME}/bin


RUN apk add maven
 
ENV MAVEN_HOME=/usr/share/java/maven-3