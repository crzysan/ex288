# source: https://hub.docker.com/_/php
FROM php:8.0-apache
RUN sed -i s/80/8080/g /etc/apache2/ports.conf && \
    sed -i s/443/8443/g /etc/apache2/ports.conf && \
    sed -i s/80/8080/g /etc/apache2/sites-enabled/000-default.conf

EXPOSE 8080
COPY *.php /var/www/html/
