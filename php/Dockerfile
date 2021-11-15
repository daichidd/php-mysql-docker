FROM php:8.0-fpm-buster

RUN apt-get update
RUN docker-php-ext-install pdo_mysql

ADD ./php.ini /usr/local/etc/php/php.ini
