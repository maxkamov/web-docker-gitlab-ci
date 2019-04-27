Docker for WEB and Gitlab CI
==========
Docker for WEB and Gitlab CI

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist jakharbek/web-docker-gitlab-ci "*"
```

or add

```
"jakharbek/web-docker-gitlab-ci": "*"
```

to the require section of your `composer.json` file.


Docker
-----

Для начало вам нужно скопировать файл .env.example и переименовать в .env

Потом запольнить всё как вам нужно для работе после вы можете запустить docker-compose

```php
docker-compose up -d
```

Gitlab CI
-----

Для работы с Gitlab CI вам нужно заполнить все переменные среды в гитлаб. Пример в файле .env.gitlab.example
