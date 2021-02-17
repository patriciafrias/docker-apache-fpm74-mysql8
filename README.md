# Docker · Apache · PHP-FPM · MySQL

Dockerized Generic development environment with Apache, PHP-FPM (v7.4), MySQL (v8.0).

// Customize your docker compose env vars
- cp docker-compose.override.yml.dist docker-compose.override.yml

// Start the containers
- docker-compose up 

// Initialize composer
- docker-compose exec php-fpm composer init

// Install dependencies
- docker-compose exec php-fpm composer install

// Test MySQL server connection
- docker-compose exec mysql mysql -uroot -ppfm

// 


