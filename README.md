step 1: composer install
step 2: cp .env.example .env
step 3: php artisan key:generate
step 4: docker-compose up -d
step 5: php artisan migrate
step 6: php artisan serve