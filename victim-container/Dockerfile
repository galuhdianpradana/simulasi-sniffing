# Dockerfile untuk Container Victim
FROM centos:7

RUN yum update -y && \
    yum install -y httpd

EXPOSE 80

CMD ["apachectl", "-D", "FOREGROUND"]
