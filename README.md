# Clinic Management System

## Overview
A web application developed for streamlining patient/client registration, appointment scheduling, and administrative workflows for healthcare providers and clinic staff.

---

## Tech Stack
* **Backend:** PHP / Laravel Framework
* **Frontend:** Blade Views, Tailwind CSS / Bootstrap, Fetch API
* **Database:** MySQL

---

## Features
* **Authentication & Authorization:** User login, registration, and input validation.
* **CRUD Operations:** Management features for core data/entities.
* **Responsive Design:** Mobile and desktop friendly UI components.

---

## Getting Started

### Prerequisites
Make sure you have the following installed on your machine:
* PHP (>= 8.x)
* Composer
* Node.js & NPM
* MySQL Database

### Installation & Setup

1. **Clone the Repository**
   ```bash
   git clone <your-repository-url>
   cd <project-folder-name>

2. **Install Backend Dependencies**
   ```bash
   composer install

3. **Install Frontend Dependencies**
   ```bash
   npm install
   npm run dev

4. **Environment Configuration
Duplicate the .env.example file and rename it to .env:**
   ```bash
   cp .env.example .env

**Open the .env file and update your database credentials:**
```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=your_database_name
DB_USERNAME=root
DB_PASSWORD=
```

5. **Generate Application Key & Run Migrations**
   ```bash
   php artisan key:generate
   php artisan migrate

6. **Start the Local Development Server**
   ```bash
   php artisan serve

---

## Authors & Team Roles
* **Backend: [Pinpin]** — Routes, Controllers, CRUD, Authentication, Validation  
* **Frontend: [Labrador]** — Blade Views, Components, Responsive Design, Fetch API  
* **Database Admin: [Sapilan]** — Database Design, Migrations, Schema  
* **System Support: [Dioquino]** — Dev Setup, Environment Config, Deployment  
* **Documentation: [Soriano]** — README.md, Code Comments, System Docs  
