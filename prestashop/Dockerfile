FROM prestashop/prestashop:1.7-7.3-fpm

RUN rm /usr/local/etc/php-fpm.d/www.conf
RUN mkdir /var/www/html/import
COPY www.conf /usr/local/etc/php-fpm.d/www.conf

CMD ["/tmp/docker_run.sh"]