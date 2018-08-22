FROM centos:latest
MAINTAINER skumar@encompassbt.com
#RUN yum update -y
RUN yum install httpd net-tools -y
RUN /bin/mkdir -p /var/www/html
RUN /bin/echo "This is a git class done by me" >> /var/www/html/index.html
EXPOSE 80
CMD apachectl "-DFOREGROUND"
