FROM tcnksm/centos-buildpack-deps:6

ENV JAVA_VERSION 1.8.0
RUN yum update && yum install -y java-"${JAVA_VERSION}"-openjdk-devel && yum clean all

