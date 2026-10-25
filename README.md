# Laravel Blog CMS

A full-stack blog platform built with **Laravel 11** and a full control panel, with role-based access for admins and writers.

![Laravel](https://img.shields.io/badge/Laravel-11-FF2D20?logo=laravel&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-8.2+-777BB4?logo=php&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?logo=tailwindcss&logoColor=white)

## Features

- **Admin panel**: edit general blog information; create, update and delete categories, posts, tags and custom pages; manage roles
- **Writer panel**: create, update and delete your own posts, and manage tags
- **Authorization** with Laravel **Policies** and **Gates**
- **Comments** through a polymorphic relationship
- **Relationships**: one-to-many and many-to-many between models
- **Queues and Mail**: weekly newsletter built and sent through Laravel Queues
- Custom validation rule
- Post view counter using cookies
- SEO-friendly slug URLs
- Seeders and factories (Faker) for demo data
- Read-only JSON API

## Roles

| Role | ID | Access |
|---|---|---|
| Admin | 1 | Full control of the blog |
| Writer | 2 | Own posts and tags |
| User | 3 | Front-end visitor |

## API

| Method | Endpoint | Description |
|---|---|---|
| GET | `/api/categories` | All categories |
| GET | `/api/categories/{id}` | Posts inside a category |
| GET | `/api/posts` | All posts |
| GET | `/api/posts/{id}` | A single post |

## Getting started

### Requirements

- PHP 8.2 or higher
- Composer
- Node.js and npm
- MySQL (or another supported database)

### Installation

```bash
git clone https://github.com/MohammedAbd20/blog-cms-main.git
cd blog-cms-main

composer install
npm install

cp .env.example .env
php artisan key:generate
```

Set your database credentials in `.env`, then:

```bash
php artisan migrate --seed    # --seed adds demo data
npm run dev
php artisan serve
```

### Demo admin account (local only)

- URL: `http://127.0.0.1:8000/admin`
- Email: `admin@example.com`
- Password: `password`

## Author

**Mohammed Hamdi Abdelrahman**: [GitHub](https://github.com/MohammedAbd20) · [LinkedIn](https://www.linkedin.com/in/mohammed-abdelrahman-web/)
