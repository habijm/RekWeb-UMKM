Step 1: 
"composer install" pada kedua file

Step 2:
"cp .env.example .env" copy paste file .env.example ke .env

Step 3:
sesuaikan nama database

Step 4:
"php artisan migrate:fresh --seed"

Step 5:
"php -S 127.0.0.2:8001 -t public" = Route API
"php artisan serve" = Route Laravel



email: admin@gmail.com
password: 12345
