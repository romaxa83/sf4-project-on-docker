# Symfony4 with Docker

Стартовый symfony-skeleton разворачиваемый на docker.
Стек:
  - Nginx
  - Php 7.2
  - Postgresql 11.2
  - PgAdmin
### Использование
развертывание приложения.

```sh
$ git clone git@github.com:romaxa83/sf4-project-on-docker.git
$ make init
```
использование консольных команд symfony.

```sh
$ docker-compose run --rm app-php-cli php bin/console <command>
```
pgadmin находиться по адресу http://localhost:555


вход
  - login: pgadmin4@pgadmin.org
  - password: admin


подключение к серверу
  - host name/address: app-postgres
  - port: 5432
  - maintenance: app
  - username: app
  - password: secret 