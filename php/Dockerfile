FROM php:7.2-fpm
MAINTAINER  adeparseval <a.parseval@gmail.com>

ARG         DEBIAN_FRONTEND=noninteractive

# Get composer
COPY        --from=composer:1.8 /usr/bin/composer /usr/bin/composer


# install git
RUN         apt update && apt install -y --no-install-recommends -o Dpkg::Options::="--force-confold" git
