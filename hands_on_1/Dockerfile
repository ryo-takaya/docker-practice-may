FROM php:7.4-cli
RUN pecl install redis-5.2.1 \
    && pecl install xdebug \
    && docker-php-ext-enable redis xdebug