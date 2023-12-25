
## Quick Start To Laravel Chatify

-   Clone or download this repo and place it into your server.
-   `composer install `
-   `cp .env.example .env `
-   Create database and modify .env with your DB name and Pusher credentials.
-   `php artisan migrate --seed`
-   `php artisan key:generate`
-   `npm install && npm run dev`
-   `php artisan storage:link`
-   `php artisan serve`

then choose a user from the database and login.

   Installation
Demo video  url: `https://www.youtube.com/watch?v=WTfDDy_-doA`
Pusher Account and it's settings
Require Chatify in your application
-  `composer require munafio/chatify`
- `php artisan chatify:install`
- `php artisan migrate`
