FROM php:7.2-apache

EXPOSE 80

RUN mkdir /var/www/html -p
WORKDIR /var/www/html

COPY ./phppra_apache2.conf /etc/apache2/sites-available/000-default.conf
COPY ./phppra_apache2_ports.conf /etc/apache2/ports.conf

