FROM php:7.2-fpm

RUN apt-get update && apt-get install -y \
        zip unzip \
        git \
        libmcrypt-dev \
        libz-dev \
        libmemcached-dev \
        && pecl install memcached \
        && docker-php-ext-install pdo \
        && docker-php-ext-enable memcached

RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer

WORKDIR /var/www
