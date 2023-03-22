# Symfony template with php 8.2 fpm and nginx
### PHP has composer and Symfony CLI downloaded
1. Build images
```shell
docker compose build
```
2. Start containers
```shell
docker compose up -d
```

3. Enter PHP container with
```shell
./php
```

4. Now you can use
```shell
composer
```
or
```shell
symfony
```

4. Close containers
```shell
docker compose down
```