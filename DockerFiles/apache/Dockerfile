FROM ubuntu:latest
RUN apt-get update
RUN apt-get -y install apache2
RUN service apache2 start
COPY / /var/www/html/

CMD ["apachectl", "-D", "FOREGROUND"]

EXPOSE 80
