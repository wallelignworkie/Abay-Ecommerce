# Abay‑Ecommerce

A Laravel-based e-commerce demo application with a Blade frontend. Built to demonstrate common e‑commerce features (product catalog, cart, orders) and to showcase project structure and development setup.

## My role / impact
- Developed the application using Laravel and Blade, implemented core product and order flows, and set up database seeding and developer-friendly run scripts.
- (Replace this with a 1–2 sentence summary of your role and impact if you prefer.)

## Tech stack
- Backend: PHP (Laravel)
- Templating: Blade
- Database: MySQL
- Dev tools: Composer, Artisan

## Quick start (development)
1. Clone
   git clone https://github.com/wallelignworkie/Abay-Ecommerce.git
2. Install dependencies
   composer install
3. Copy env
   cp .env.example .env
4. Generate app key
   php artisan key:generate
5. Configure .env for your MySQL database (DB_HOST, DB_DATABASE, DB_USERNAME, DB_PASSWORD)
6. Run migrations and seeders
   php artisan migrate --seed
7. Serve the app
   php artisan serve
8. Visit http://127.0.0.1:8000

## Example dev credentials
(Confirm whether you want real example credentials added or leave these placeholders.)
- Email: admin@example.test
- Password: password

## Running tests
- No test suite included yet. (Or: php artisan test — add tests as available.)

## Notable design decisions
- Server-rendered Blade views for fast iteration and SEO-friendly pages.
- Eloquent models with standard Laravel relationships for products, orders, and users.
- Database seeding to provide test data for local development.

## Production notes
- Use a managed MySQL instance and configure .env APP_ENV=production, DB credentials, and queue/mail settings.
- Run migrations with backups and configure a queue worker for background jobs where applicable.

## Useful commands
- php artisan migrate --seed
- php artisan storage:link
- php artisan queue:work

## Contributing
1. Fork the repo
2. Create a branch: docs/add-readme-abay-ecommerce
3. Make changes, push, and open a PR

## Contact
- Maintainer: wallelignworkie
- (Add demo URL or screenshots here if available.)
