# Dockerize Laravel

File examples, that can be used to run Laravel app on your host system, using Docker.

## Usage

> Check out [YouTube](https://youtu.be/n9ZubBaWsgE) for more details.

* Copy or symlink `docker` directory to your project root;
* Copy `docker-compose.yml` file to your project root;
* Sync docker compose file with your `.env`;
* To get your user ID run `id` command.

## Commands

```shell

git clone -b v11.4.0 --depth=1 https://github.com/laravel/laravel.git larademo

docker run --rm --interactive --tty --volume $PWD:/app -u 1000:33 composer install

docker compose -p mdev up -d
docker compose -p mdev stop

```

## Useful Links

* [Laravel App](https://github.com/laravel/laravel)
* [Laravel Docs: Deployment Nginx](https://laravel.com/docs/11.x/deployment#nginx)

### Docker Hub 

* [Composer Image](https://hub.docker.com/_/composer)
* [MariaDB Image](https://hub.docker.com/_/mariadb)
* [Nginx Image](https://hub.docker.com/_/nginx)
* [PHP Image](https://hub.docker.com/_/php)
* [PhpMyAdmin Image](https://hub.docker.com/_/phpmyadmin)
