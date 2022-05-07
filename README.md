# docker-php8.0-apache

A Debian LAMP container

It's on [docker-hub](https://hub.docker.com/repository/docker/niclab/php8.0/) and [github](https://github.com/Akito-K/docker-php8.0)

## tags and links
* `latest` [(main/Dockerfile)](https://github.com/Akito-K/docker-php8.0/blob/main/Dockerfile)

## how to build

```sh
git clone git@github.com:Akito-K/docker-php8.0.git
cd docker-php8.0
docker build --rm -t niclab/php8.0 .
```

## running

```sh
docker-compose up -d
```