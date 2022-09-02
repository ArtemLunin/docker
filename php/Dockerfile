FROM php:8.0-apache
RUN apt-get update && apt-get install -y libfreetype6-dev libjpeg62-turbo-dev libpng-dev libwebp-dev
RUN docker-php-ext-configure gd --with-jpeg --with-webp --with-freetype
RUN docker-php-ext-install mysqli pdo_mysql gd && docker-php-ext-enable pdo_mysql gd mysqli