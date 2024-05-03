## Articles Laravel API and Authentication

 This is articles project to show how you could write an API using Laravel.

 There will be some minor differences, specially regarding downloaded packages, as I used the
 excellent [Laravel Ide Helper](https://github.com/barryvdh/laravel-ide-helper) to setup
 PhpStorm bindings and other features.

## Running the API

It's very simple to get the API up and running. First, create the database (and database
user if necessary) and add them to the `.env` file.

```
DB_DATABASE=your_db_name
DB_USERNAME=your_db_user
DB_PASSWORD=your_password
```

Then install, migrate, seed, all that jazz:

1. `composer install`
2. `php artisan migrate`
3. `php artisan db:seed`
4. `php artisan serve`

or You can speciify your port in order to running the API by using 
`php artisan serve --port 9090`

or running this one command to run migration and seeder
`php artisan migrate:refresh --seed`

The API will be running on `localhost:8000` or `localhost:9090`
