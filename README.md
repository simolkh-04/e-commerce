# E-Commerce

A modern e-commerce web application built with Laravel framework. 

## 📊 Technology Stack

- **PHP** (27.4%) - Backend logic and server-side processing
- **CSS** (54.2%) - Styling and design
- **Blade** (17.4%) - Laravel templating engine
- **JavaScript & Other** (1.0%) - Frontend interactivity

## 🚀 Features

This is a Laravel-based e-commerce platform designed to provide a complete online shopping experience. 

## 📋 Requirements

- PHP >= 8.1
- Composer
- Node.js & NPM
- MySQL or PostgreSQL database
- Web server (Apache/Nginx)

## 🛠️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/NIZAR-BENAKKADOU/e-commerce.git
   cd e-commerce
   ```

2. **Install PHP dependencies**
   ```bash
   composer install
   ```

3.  **Install JavaScript dependencies**
   ```bash
   npm install
   ```

4. **Environment setup**
   ```bash
   cp .env.example .env
   php artisan key:generate
   ```

5. **Configure database**
   - Edit `.env` file with your database credentials
   ```
   DB_CONNECTION=mysql
   DB_HOST=127.0.0.1
   DB_PORT=3306
   DB_DATABASE=your_database_name
   DB_USERNAME=your_username
   DB_PASSWORD=your_password
   ```

6. **Run migrations**
   ```bash
   php artisan migrate
   ```

7. **Build assets**
   ```bash
   npm run build
   ```

8. **Start the development server**
   ```bash
   php artisan serve
   ```

   Visit `http://localhost:8000` in your browser. 

## 📁 Project Structure

```
e-commerce/
├── app/                # Application core code
├── bootstrap/          # Framework bootstrap files
├── config/            # Configuration files
├── database/          # Migrations, factories, and seeders
├── public/            # Public assets (CSS, JS, images)
├── resources/         # Views, raw assets
├── routes/            # Application routes
├── storage/           # Generated files, logs, cache
├── tests/             # Automated tests
└── vendor/            # Composer dependencies
```

## 🧪 Testing

Run the test suite:
```bash
php artisan test
```

Or use PHPUnit directly:
```bash
./vendor/bin/phpunit
```

## 🔧 Development

For development with hot reload:
```bash
npm run dev
```

## 📝 License

This project is open-source and available for use and modification.

## 👤 Author

**NIZAR BENAKKADOU**
- GitHub: [@NIZAR-BENAKKADOU](https://github.com/NIZAR-BENAKKADOU)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! 

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📞 Support

If you have any questions or need help, please open an issue in the repository.

---

Built with ❤️ using Laravel
