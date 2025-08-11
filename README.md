# laravel-wordpress-assessment

This repository contains two separate projects:

-   **Laravel Task** (in `laravel-task/`)
-   **WordPress Task** (in `wordpress-task/`)

## How to Run the Projects

---

## Laravel Task

### Test User Credentials

-   **Email:** emma.carter@example.com
-   **Password:** securepass

### Prerequisites

-   PHP >= 8.0
-   Composer
-   Node.js & npm (for frontend assets)

### Setup & Run

1. Navigate to the Laravel project directory:
    ```powershell
    cd laravel-task
    ```
2. Install PHP dependencies:
    ```powershell
    composer install
    ```
3. Install Node.js dependencies:
    ```powershell
    npm install
    ```
4. Run database migrations and seeders:
    ```powershell
    php artisan migrate --seed
    ```
5. Start the Laravel development server:
    ```powershell
    php artisan serve
    ```
6. (Optional) Build frontend assets:
    ```powershell
    npm run build
    ```

---

## WordPress Task

### Prerequisites

-   Local WordPress installation (e.g., XAMPP, WAMP, MAMP)

### Setup & Run

1. Copy the contents of `wordpress-task/` into your WordPress theme directory (e.g., `wp-content/themes/your-theme-name`).
2. Activate the theme from the WordPress admin dashboard.
3. Visit your site to view the custom theme and functionality.

---

## Additional Notes

-   For more details, refer to the individual `README.md` files in each project folder.
-   Make sure your local environment meets the prerequisites for each project.
