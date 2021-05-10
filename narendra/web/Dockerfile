FROM centos
MAINTAINER nari <nari@gmail.com>
RUN yum install httpd git -y 
RUN git clone https://github.com/narendra323/geme-java.git /var/www/html
CMD ["httpd" , "-DFOREGROUND"]
