# https://github.com/CentOS/CentOS-Dockerfiles/blob/master/mongodb/centos6/Dockerfile
# https://github.com/CentOS/CentOS-Dockerfiles/blob/master/nodejs/centos6/Dockerfile
FROM centos:centos6

RUN yum -y update; yum clean all
RUN yum -y install epel-release; yum clean all

RUN yum -y install mongodb-server; yum clean all
RUN mkdir -p /data/db

EXPOSE 27017
ENTRYPOINT ["/usr/bin/mongod"]

RUN yum -y install nodejs npm; yum clean all
