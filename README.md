
---

````markdown
# Laravel 10 + Inertia.js + React Boilerplate

A modern starter kit for building full-stack applications using **Laravel 10**, **Inertia.js**, and **React**. This boilerplate is designed to speed up development by providing a clean, scalable, and well-structured foundation.

---

## 🚀 Stack

- **Backend**: Laravel 10
- **Frontend**: React 18 (via Inertia.js)
- **Routing**: Laravel Router (Backend) + Inertia Navigation (Frontend)
- **Bundler**: Vite
- **Authentication**: Laravel Breeze (Inertia/React version)
- **Styling**: Tailwind CSS (optional, included by default)
- **API communication**: Inertia.js (server-driven SPA)

---

## 📦 Installation

1. **Clone the repository**

```bash
git clone https://github.com/Sajidimon/laravel-react-inertia-boilerplate-.git
cd laravel-react-inertia-boilerplate
````

2. **Install PHP & JS dependencies**

```bash
composer install
npm install
```

3. **Environment setup**

```bash
cp .env.example .env
php artisan key:generate
```

4. **Database setup**

Edit your `.env` file with the correct database credentials, then run:

```bash
php artisan migrate
```

5. **Start development servers**

```bash
php artisan serve
npm run dev
```

---

## 🧩 Features

* Inertia-powered React SPA
* Laravel Breeze Authentication
* Vite for lightning-fast frontend build
* Tailwind CSS for rapid UI development
* Clean and modular folder structure
* CSRF protection and secure routing

---

## 🧪 Scripts

| Command               | Description                   |
| --------------------- | ----------------------------- |
| `npm run dev`         | Run Vite in development mode  |
| `npm run build`       | Compile assets for production |
| `php artisan serve`   | Serve Laravel backend locally |
| `php artisan migrate` | Run database migrations       |

---

## 📁 Folder Structure

```
├── app/
├── resources/
│   └── js/
│       ├── Pages/
│       ├── Components/
│       └── App.jsx
├── routes/
│   └── web.php
├── public/
├── database/
├── .env
└── vite.config.js
```

---

## 🤝 Contributing

Feel free to fork this project, open issues, or submit PRs. All contributions are welcome!

---

## 📄 License

This project is open-sourced under the [MIT license](LICENSE).

```

---

Let me know if you want this tailored further—like adding Docker support, CI/CD setup instructions, or using a different auth package (e.g. Jetstream, Sanctum).
```
