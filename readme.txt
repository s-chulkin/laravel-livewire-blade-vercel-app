composer create-project laravel/laravel laravel-livewire-blade-vercel-app
cd laravel-livewire-blade-vercel-app
composer require laravel/jetstream
php artisan jetstream:install livewire

php artisan key:generate

.env
APP_KEY=

# Set environment variables in vercel:
DB_HOST=
DB_DATABASE=
DB_USERNAME=
DB_PASSWORD=
