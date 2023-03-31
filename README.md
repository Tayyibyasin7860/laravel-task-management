# Task Management System

## Requirements
- PHP 8.1+
- Laravel 10+
- Vue 3+

## Installation
2. Clone repository from git
1. Change current directory to project directory
3. Install composer dependencies: **composer install**


3. Create a copy of the `.env.example` file as `.env`: **cp .env.example .env**


4. Generate an application key: **php artisan key:generate**


5. Update the `.env` file with your database credentials and other settings:
   **DB_DATABASE=your_database_name, 
   DB_USERNAME=your_database_username, 
   DB_PASSWORD=your_database_password**

6. Run database migrations and seeders: **php artisan migrate --seed**


7. Install NPM dependencies and build assets:
   **npm install, 
   npm run build**
8. Start the development server: **php artisan serve**
10. Open the application in your browser: **http://localhost:8000/**
