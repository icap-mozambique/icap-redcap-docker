FROM httpd:2.4-alpine

MAINTAINER Stelio Moiane <steliomo@gmail.com>

ADD httpd.conf /usr/local/apache2/conf/httpd.conf

ADD httpd-vhosts.conf /usr/local/apache2/conf/httpd-vhosts.conf

RUN apk add --update php7 php7-fpm php-ctype php-curl php-dom php-fileinfo php-iconv php-json php-mbstring php-openssl php-simplexml php-xmlreader php-xmlwriter php-mysqli php-session php-zip