FROM php:8.0.0-apache
ARG DEBIAN_FRONTEND=noninteractive
RUN apt-get update && apt-get upgrade -y

COPY . /var/www/html

CMD ["apache2-foreground"]
