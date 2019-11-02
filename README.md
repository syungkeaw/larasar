# Quasar App (client) & Laravel Backend (server)

A Laravel + Quasar Framework App

## Install the dependencies
```bash
composer install
composer require laravel/ui --dev
php artisan ui vue --auth
cp .env.example .env
php artisan key:generate
php artisan passport:keys or php artisan passport:install
npm install
npm run dev
```

### Start the app in development mode (hot-code reloading, error reporting, etc.)
```bash
quasar dev
php artisan serve
```

### Lint the files
```bash
npm run lint
```

### Build the app for production
```bash
quasar build
```

### Customize the configuration
See [Configuring quasar.conf.js](https://quasar.dev/quasar-cli/quasar-conf-js).

Backend Server:http://localhost:8000
Frontend Server:http://localhost:8080
Network:http://192.168.2.11:8080