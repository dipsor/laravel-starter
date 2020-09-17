## Laravel Starter

- dockerized laravel app for local development

### Using: 
- laravel 7.0
- php 7.4
- mysql 5.7
- redis
- nginx

### Installation:
download repo
```
 git clone git@github.com:dipsor/laravel-starter.git 
```

build docker containers
```
docker-compose up --build
```
enter web container
```
docker exec -it appname_app_1 bash 
```

inside of the container install the deppendencies
```
composer install
yarn
```

migrate and seed database
``` 
php aritsan migrate --seed
```
