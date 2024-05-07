# FIX Bug: GD Library extension not available with this PHP installation.

> 1. Remove ";" from ;extension=gd in php.ini file (xampp/php)
> 2. in console run command::
>    php artisan route:clear
>    php artisan cache:clear
>    php artisan optimize:clear

# Run

1. first console: php artisan serve
2. second console: npm run dev
