config apache
https://tech-cookbook.com/2021/10/25/how-to-setup-mamp-macos-apache-mysql-php-on-macos-12-monterey-2021/

Copy .env.example to .env:

cp -a .env.example .env

Generate a key:

php artisan key:generate

Only then run:

php artisan serve
