## Laravel Skeleton

Мой телеграм - [@repsys](https://t.me/repsys) (На случай если что-то не работает)

### Как запустить:

1. Клонировать проект:
    ```
    git clone https://github.com/Repsys/laravel-skeleton
    ```
2. Выполнить в корне проекта:
    ```
    cp .env.example .env
    composer i
    docker-compose up -d
    sudo chmod 777 -R ./storage/
    docker-compose exec php-fpm php artisan key:generate
    docker-compose exec php-fpm php artisan migrate
    ```
