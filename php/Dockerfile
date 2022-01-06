FROM php:7.1-apache

RUN cp "$PHP_INI_DIR/php.ini-development" ". / configure--with - pdo - odbc = ibm - db2, /opt/IBM / db2 / V8 .1 /"


# install mysql pdo extension 
RUN docker-php-ext-install mysqli pdo pdo_mysql pdo_pgsql pdo_odbc


COPY html  /var/www/html/

RUN apt-get -y install unixodbc-dev
RUN pecl install sqlsrv pdo_sqlsrv

COPY php.ini /usr/local/etc/php/