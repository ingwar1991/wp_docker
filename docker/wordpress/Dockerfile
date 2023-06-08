FROM wordpress:php8.1-apache
RUN apt-get update && \
    apt-get install -y vim
COPY apache-vhost.conf etc/apache2/sites-available/000-default.conf
COPY php-settings.ini /usr/local/etc/php/php.ini
