FROM php:8.2-fpm
# Debian GNU/Linux 12 (bookworm)

RUN apt-get update 

RUN pecl install xdebug \
    && docker-php-ext-enable xdebug;

RUN echo "zend_extension=xdebug" > /usr/local/etc/php/conf.d/99-xdebug.ini;