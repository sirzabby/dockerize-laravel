# Dockerize Laravel

File examples, that can be used to run Laravel app on your host system, using Docker.

## Commands

```shell

git clone -b v11.3.3 --depth=1 https://github.com/laravel/laravel.git larademo

docker run --rm --interactive --tty --volume $PWD:/app -u 1000:33 composer install

docker compose -p mdev up -d
docker compose -p mdev stop

```
