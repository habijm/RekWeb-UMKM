Step 1: 
"git clone https://github.com/habijm/RekWeb-UMKM.git"

Step 2: 
"composer install" pada kedua file

Step 3:
"cp .env.example .env" copy paste file .env.example ke .env

Step 4:
sesuaikan nama database

Step 5:
"php artisan migrate:fresh --seed"

Step 6:
"php -S 127.0.0.2:8001 -t public" = Route API
"php artisan serve" = Route Laravel


email: admin@gmail.com
password: 12345
