# Laravel Project

## How to use

### Go to the laradock folder and run:

  docker compose up -d
  docker compose exec workspace bash

### Inside the container

  composer create-project --prefer-dist laravel/laravel backend "11.*"
  exit


### Verify that the laravel-project folder contains a backend folder. Confirm your changes with "Laravel project initiated."

### To launch the development server:

  docker compose exec workspace bash
  cd backend
  php artisan serve --host=0.0.0.0
