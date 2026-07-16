# Task Management App

A robust and efficient Task Management application built with Laravel to help users organize, track, and manage their daily goals and responsibilities.

---

## Author

**Jay Millena**

*Designed on July 16, 2026*

---

## Getting Started

Follow these steps to set up the project on your local machine.

### Prerequisites

* PHP 8.2 or higher
* Composer
* Node.js and NPM
* A database (MySQL, PostgreSQL, or SQLite)

### Installation

1. **Clone the repository:**
```bash
git clone <repository-url>
cd <project-folder>

```


2. **Install PHP dependencies:**
```bash
composer install

```


3. **Install frontend dependencies:**
```bash
npm install && npm run dev

```


4. **Environment Configuration:**
Copy the example environment file and generate your application key:
```bash
cp .env.example .env
php artisan key:generate

```



---

## Basic Configuration

To get the application running, update your `.env` file with your specific environment settings:

1. **Database Setup:** Update the following lines to match your database credentials:
```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=your_database_name
DB_USERNAME=your_username
DB_PASSWORD=your_password

```


2. **Run Migrations:**
Once your database is configured, run the following command to set up the necessary tables:
```bash
php artisan migrate

```


3. **Application URL:** Ensure the `APP_URL` matches your local development environment:
```env
APP_URL=http://localhost:8000

```



---

## Usage

After completing the configuration, start your local development server:

```bash
php artisan serve

```