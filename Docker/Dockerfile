FROM centos
MAINTAINER Piyush
RUN apt install apache2 -y
RUN apt-get update -y
COPY index.html /var/www/html/

CMD [“/usr/sbin/httpd”,” -D”,” FOREGROUND”]
EXPOSE 80
