# Campus Service Portal

A web-based campus service portal built with Laravel, developed as part of my BBC 3 AWAD coursework.

## Features
- Home page with campus service information
- Contact page with a working form
- Form submissions are validated and saved to a MySQL database
- Built following Laravel routing, controllers, and Blade templating conventions

## Tech Stack
- Laravel 12
- PHP 8.2
- MySQL
- Blade templates
- Tailwind CSS

## Getting Started
1. Clone the repository
2. Run `composer install`
3. Copy `.env.example` to `.env` and configure your database
4. Run `php artisan key:generate`
5. Run `php artisan migrate`
6. Run `php artisan serve`
7. Visit `http://127.0.0.1:8000`
