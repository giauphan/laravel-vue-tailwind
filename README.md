# Laravel Vue Tailwind Setup

This repository contains a starter template for setting up a web application using Laravel, Vue.js, and Tailwind CSS.

## Features

- Laravel 11.x
- Vue.js 3.x
- Tailwind CSS 3.x

## Requirements

- PHP >= 8.2
- Composer
- Node.js & npm
- Git

## Setup Instructions

1. **Clone the repository**:

   ```bash
   git clone https://github.com/giauphan/laravel-vue-tailwind
   ```
   # Navigate into the project directory
   ```
    cd laravel-vue-tailwind
   ```
# Install PHP dependencies
```
composer install
```
# Install JavaScript dependencies
```
npm install
```
# Compile assets
```
npm run dev
```
# Set up environment variables

# Duplicate the ``.env.example file and rename it to .env.``
# Generate an application key
```
php artisan key:generate
```
# Configure your database connection in the .env file.

# Run migrations (if using a database)
```
php artisan migrate
```
# Start the development server
```
php artisan serve
```

Access your application

Open your web browser and navigate to ``http://localhost:8000.``

Deployment

To deploy your application, you can use various hosting platforms such as:

- [Heroku](https://www.heroku.com/)
- [DigitalOcean](https://www.digitalocean.com/)
- [Vercel](https://vercel.com/)

Ensure that you set up appropriate deployment scripts and configurations for your chosen platform.

Contributing

Contributions are welcome! Feel free to submit issues and pull requests.

License 

This project is open-sourced software licensed under the MIT license.
