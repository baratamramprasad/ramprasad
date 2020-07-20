FROM centos
USER root
RUN yum install -y \
       java-1.8.0-openjdk \
       java-1.8.0-openjdk-devel

EXPOSE 8080
ENV JAVA_VER 8
    JAVA_HOME /usr/lib/jvm/openjdk-1.8.0
USER 1010
ENTRYPOINT ./entryPoint.sh