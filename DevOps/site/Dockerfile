FROM php:7.1.33

RUN cp "$PHP_INI_DIR/php.ini-development" "$PHP_INI_DIR/php.ini"

# install mysql pdo extension 
RUN docker-php-ext-install pdo_mysql

COPY html  /var/www/html