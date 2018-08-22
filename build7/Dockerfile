FROM centos:latest
MAINTAINER skumar@encompassbt.com
RUN yum update -y
RUN yum install httpd net-tools -y
RUN /bin/mkdir -p /var/softwares/
RUN yum install vsftpd -y
ADD file1 /var/softwares
ADD sfw.tar.gz /var/softwares
WORKDIR /var/softwares
ADD http://dl.fedoraproject.org/pub/epel/epel-release-latest-7.noarch.rpm .
RUN /usr/bin/rpm -ivh epel-release-latest-7.noarch.rpm
