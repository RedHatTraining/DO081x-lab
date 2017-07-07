FROM rhel7.3

MAINTAINER Your Name <youremail>
LABEL description="A basic Apache HTTP server container on RHEL 7"

RUN yum -y update && \
    yum install -y httpd && \
    yum clean all

EXPOSE 80

ENTRYPOINT ["httpd"]
CMD  ["-D", "FOREGROUND"]
