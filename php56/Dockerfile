FROM thetimeiswater/php:php56-fpm

COPY php.ini "$PHP_INI_DIR/php.ini"
COPY www.conf /usr/local/etc/php-fpm.d/www.conf

WORKDIR /www

#RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer
#
#RUN apk add --no-cache \
#        $PHPIZE_DEPS \
#        iputils
#
#RUN apk add --no-cache libstdc++ libzip-dev vim
#
## 安装扩展
## https://github.com/mlocati/docker-php-extension-installer
#RUN docker-php-ext-install pdo_mysql
#RUN docker-php-ext-install bcmath
#RUN docker-php-ext-install mysqli
#RUN docker-php-ext-install opcache
#
## # 安装 redis 扩展
#RUN pecl install redis-2.2.8
#RUN pecl install zip
#RUN pecl install swoole-1.10.5
#
## 开启扩展
#RUN docker-php-ext-enable pdo_mysql bcmath mysqli opcache redis zip swoole



