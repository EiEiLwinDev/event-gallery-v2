
# Vue and Laravel 8 Setup Guide

# Tech
Vue, Laravel, Mysql, Bootstrap

## Step 1: Change Database Connection

Update your `.env` file with the following database connection settings:

```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=gallery
DB_USERNAME=root
DB_PASSWORD=
```

## step 2
run the following cmd

```
composer install
npm install
php artisan migrate
php artisan db:seed
php artisan storage:link
```

## step 3
```
npm run dev
php artisan serve
```

## step 4
Enter on your browser
```
http://127.0.0.1:8000
```

## step 5

login with the following email and pwd
```
email - admin@example.com
pwd - admin123
```

## note ##
* member can be created on sign up form
* admin cannot be created, default admin user is already created as mention above.
