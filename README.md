# Getting started


setup environment
```batch
gh repo clone nursyah21/jlnr
cd jlnr
composer install
npm install
copy .env.example .env
php artisan migrate --seed
php artisan key:generate
```

for development
```batch
php artisan serve
npm run dev
```
