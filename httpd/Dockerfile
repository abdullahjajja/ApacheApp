FROM centos:centos7
RUN yum -y install php php-devel php-gd php-pdo php-soap php-xmlrpc php-xml httpd httpd-devel
EXPOSE 80
CMD ["/usr/sbin/httpd","-D","FOREGROUND"]

