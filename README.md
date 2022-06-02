# docker-laravel

やること

```
$ docker-compose run --rm php composer create-project --prefer-dist laravel/laravel .
```

変更箇所

```.env
DB_CONNECTION=mysql
DB_HOST=db
DB_PORT=3306
DB_DATABASE=db
DB_USERNAME=docker
DB_PASSWORD=docker
```
