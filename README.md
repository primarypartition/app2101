# Project Setup

> composer create-project laravel/laravel="7.0.*" project_name
> composer create-project laravel/laravel project_name

> composer require laravel/ui
> composer require laravel/ui:^3.0

> composer require laravel/breeze --dev
> php artisan breeze:install
> php artisan ui vue --auth

> npm install && npm run dev


## .env update for database credentials

php artisan migrate


## xampp Setup 

- composer require
- php 7.3 require

### hosts File

```
127.0.0.1        local.app2101
```


### httpd-vhosts.conf

```
<VirtualHost *:80>   
	ServerName local.app2101
	DocumentRoot "C:\xampp\htdocs\app2101\public" 
</VirtualHost>
```


## Git Setup

```
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/primarypartition/app2101.git
git push -u origin main
```
