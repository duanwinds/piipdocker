FROM duanli/php-fpm

MAINTAINER duan duan.li@gmail.com

ENV HOME /root
ENV LC_ALL          C.UTF-8
ENV LANG            en_US.UTF-8
ENV LANGUAGE        en_US.UTF-8

Volume /var/www/newsite
Run apt-get -y install composer unzip && \
    cd /var/www/newsite && \
    composer create-project laravel/laravel newsite && \
    composer require jenssegers/mongodb

CMD ["echo"]
