#make .env
```
cp .env.example .env
```
#change in .env
```
DB_CONNECTION=mysql
DB_HOST=db-host
DB_PORT=3306
DB_DATABASE=database
DB_USERNAME=docker
DB_PASSWORD=docker

```

#composer 
```
$ composer install
```

#keygenerate
```
$ php artisan key:generate
```
