# Laravel React

## rename .env.example to .env

Change the following in the .env file

```
DB_DATABASE=laravel_react
DB_USERNAME=root
DB_PASSWORD=
...
...

## Create mysql database `in model laravel`
> NOTE: If you want to use sample database, use `php artisan migrate` file

# To Start Laravel
- cd laravel
- composer install
- php artisan key:generate
- php artisan migrate
- php artisan serve
### keep that running in the terminal

# To Start React
Open new terminal
- cd react
- npm install
- npm start
```
