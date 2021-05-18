## PHP 7.4 with Apache
This docker runs Symfony applications through apache and php-7.4

## How to install a new Symfony web application

1. Start the environment: ```docker-compose up -d```
2. Login on the container with ```docker exec -it dev_apache_php74 /bin/bash```
3. Run: ```composer create-project symfony/website-skeleton:"^4.4" /var/www/html/``` (4.4 is the latest LTS symfony version)
