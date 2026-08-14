# devwebcamp

A comprehensive event management website built with Laravel and Vue.js, designed by full‑stack developer Bruno Rossani.

## Tech Stack
![Laravel](https://img.shields.io/badge/Laravel-8.0-red)
![Vue.js](https://img.shields.io/badge/Vue.js-2.6-brightgreen)
![PHP](https://img.shields.io/badge/PHP-7.4%20%2F%208.0-blue)
![MySQL](https://img.shields.io/badge/MySQL-5.7%20%2F%208.0-blue)
![Gulp](https://img.shields.io/badge/Gulp-4.0-lightgrey)

## Features
- Create, edit, and publish events with rich details.
- Manage speakers (ponentes) and their sessions.
- Registration system with email notifications and gift handling.
- Admin dashboard with analytics and pagination.
- RESTful API endpoints for events, speakers, and gifts.
- Role‑based authentication and authorization.

## Installation

### Prerequisites
- PHP 7.4+ / 8.0
- Composer
- Node.js & npm
- MySQL
- Gulp CLI (`npm install -g gulp-cli`)

### Steps
1. Clone the repository  
   ```bash
   git clone https://github.com/yourusername/devwebcamp.git
   cd devwebcamp
   ```
2. Install PHP dependencies  
   ```bash
   composer install
   ```
3. Install front‑end assets  
   ```bash
   npm install
   ```
4. Copy the example environment file and set your variables  
   ```bash
   cp .env.example .env
   php artisan key:generate
   ```
5. Configure the database in `.env` and run migrations  
   ```bash
   php artisan migrate
   ```
6. Build assets with Gulp  
   ```bash
   gulp
   ```
7. Start the development server  
   ```bash
   php artisan serve
   ```

Visit `http://localhost:8000` to explore the application.

## Contributing
Feel free to open issues or submit pull requests. Please follow the existing coding style and run tests before contributing.

## License
This project is licensed under the MIT License.