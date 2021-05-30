FROM centos:7
MAINTAINER nnyimc
RUN yum update -y && yum install httpd -y && yum clean all
ENTRYPOINT apachectl "-DFOREGROUND"
