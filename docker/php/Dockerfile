FROM php:7.4-apache

RUN apt-get update -yq \
	&& docker-php-ext-install mysqli pdo pdo_mysql \
    && apt-get clean -y

EXPOSE 80