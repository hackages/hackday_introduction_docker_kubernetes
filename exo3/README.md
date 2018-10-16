# Hands on Docker compose
## Docker compose exercices

### Building a python/flask application

Based on the python files (especially app.py), try to build an app using redis, mongodb and nginx as loadbalancer. 

The nginx configuration is already done. 

Please, try to follow the below schema : 

Tips, you can create a dockerfile per container.

When it's running the application should be like this : 

### Building a nodejs application

Based on the nodejs files, try to build an app using redis, mongodb and nginx as loadbalancer. 

The nginx configuration is already done.

Please, try to follow the below schema : 

Tips, you can create a dockerfile per container.

While running the application should be like this : 

### Deploy wordpress and mysql database

Based on the official docker wordpress image https://hub.docker.com/_/wordpress/, try to use docker compose to deploy it. 

Hint, those environment variables will be needed : 

```
MYSQL_ROOT_PASSWORD: somewordpress
MYSQL_DATABASE: wordpress
MYSQL_USER: wordpress
MYSQL_PASSWORD: wordpress

WORDPRESS_DB_HOST: db:3306
WORDPRESS_DB_USER: wordpress
WORDPRESS_DB_PASSWORD: wordpress
```