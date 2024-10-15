FROM php:8.2-fpm

WORKDIR /var/www/html

RUN apt-get update && \
    apt-get install nano -y && \
    docker-php-ext-install mysqli