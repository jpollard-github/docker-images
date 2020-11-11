FROM centos:8
LABEL maintainer="Jason Pollard" description="Base image for all JEE server images, from adam-bien.com"
RUN yum update -y \
  && yum -y install unzip \
  && yum -y install java-1.8.0-openjdk-devel \
  && yum clean all
ENV JAVA_HOME /usr/lib/jvm/java-1.8.0
ENV PATH "$PATH":/${JAVA_HOME}/bin:.: