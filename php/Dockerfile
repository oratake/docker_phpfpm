FROM php:8-fpm-alpine
RUN apk upgrade --update && apk --no-cache add \
  autoconf \
  make \
  g++ \
  gcc
RUN docker-php-ext-install \
  pdo \
  pdo_mysql