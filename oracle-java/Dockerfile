FROM oraclelinux:7-slim

RUN yum -y install wget && \
    wget --header "Cookie: oraclelicense=accept-securebackup-cookie" \
  http://download.oracle.com/otn-pub/java/jdk/8u151-b12/e758a0de34e24606bca991d704f6dcbf/jdk-8u151-linux-x64.rpm && \
    yum -y localinstall jdk-8u151-linux-x64.rpm && \
    rm jdk-8u151-linux-x64.rpm && \
    yum clean all && \
    rm -rf /var/cache/yum/*
