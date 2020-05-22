#create-project

```
docker-laravel$ mkdir project
docker-laravel$ docker-compose up --build
docker-laravel$ docker exec -it php bash
(docker) $ composer create-project laravel/laravel ./
```

#change in project/.env

```
DB_CONNECTION=mysql
DB_HOST=db-host
DB_PORT=3306
DB_DATABASE=database
DB_USERNAME=docker
DB_PASSWORD=docker

```

