FROM ubuntu:latest
RUN apt-get update
RUN apt-get -y install apache2
RUN apt-get install -y php7.0 \
    libapache2-mod-php7.0
RUN service apache2 start
COPY / /var/www/html/

CMD ["apachectl", "-D", "FOREGROUND"]

EXPOSE 80