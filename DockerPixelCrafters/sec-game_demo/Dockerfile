FROM ubuntu/apache2:latest

COPY webgl.conf /etc/apache2/sites-enabled/000-default.conf

COPY apache2.conf /etc/apache2/apache2.conf

COPY webgl/ /var/www/html
COPY .htaccess /var/www/html/.htaccess

RUN a2enmod rewrite
RUN a2enmod headers

EXPOSE 80