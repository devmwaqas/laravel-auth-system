# Laravel Authentication System (Breeze)

This is a simple authentication system built with Laravel Breeze. It includes user registration, login, logout, email verification, and password reset functionality.

## 🔧 Features

- User registration
- Login / Logout
- Password reset via email
- Email verification
- Tailwind CSS & Alpine.js frontend
- Protected `/dashboard` route

## 🚀 Getting Started

### 1. Clone the Repo

```bash
git clone https://github.com/devmwaqas/laravel-auth-system.git
cd laravel-auth-system
```

### 2. Install Dependencies

```bash
composer install
npm install
npm run dev
```

### 3. Create `.env` File

Copy `.env.example` to `.env` and configure your DB and mail:

```bash
cp .env.example .env
php artisan key:generate
```

Set your database and mail settings in `.env`:

```env
DB_DATABASE=laravel_auth
DB_USERNAME=root
DB_PASSWORD=

MAIL_MAILER=smtp
MAIL_HOST=smtp.mailtrap.io
MAIL_PORT=2525
MAIL_USERNAME=your_username
MAIL_PASSWORD=your_password
```

### 4. Run Migrations

```bash
php artisan migrate
```

### 5. Start Development Server

```bash
php artisan serve
```

Visit `http://localhost:8000/register` to create an account and get started.

## 📂 Auth Routes

- `/register` – Create new account  
- `/login` – Login to existing account  
- `/forgot-password` – Reset password  
- `/email/verify` – Email verification  
- `/dashboard` – Protected page (login required)

## 📬 Contact

Want to build more features like this?  
Let’s connect → [codewithwaqas.com](https://codewithwaqas.com)
