Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

Laravel is accessible, powerful, and provides tools required for large, robust applications.

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).

### Option 1

1. `git clone`
2. `create a .env file copy content from .env.example and update the values`
3. `composer install && composer update`
4. `php artisan cron:refresh-database`
5. if npm version < 7 `npm install && npm run dev` else `npm install --legacy-peer-deps && npm run dev`
6. `php artisan key:gen`
7. `php artisan serve`
