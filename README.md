# APACHE HTTPD and PHP-FPM 8.1
Apache HTTPD and php-fpm container stack using docker-compose

## HOW TO USE
Simply use docker-compose command to create this docker container stack.

```
docker-compose -f nginx-compose.yml up -d
```

* It will exposing port `8083` from your host to port `80` inside nginx container. 
* Put your php project to `www` directory.
* To add more configuration you can change httpd config in `httpd.conf` file and php configuration in `php.ini` inside `config` directory.
* Open `localhost:8083` to check if this container is working.