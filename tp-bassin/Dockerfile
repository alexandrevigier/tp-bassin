FROM php:7.2-apache

RUN apt-get update && \
	docker-php-ext-install pdo_mysql && \
	groupadd dev && \
    useradd mario --groups dev

CMD echo "bonjour"