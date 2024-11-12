## Routes for Admins - Teachers - Users

- Admin login ( http://localhost:8000/admin/login )
- Teacher login and register (http://localhost:8000/teacher/login )
- User login and register page (http://localhost:8000/login )

## How to run the code

- git clone
- cd multi_auth_app
- cp .env.example `.env`
- run : `composer install` || `composer update`
- run : `php artisan key:generate`
- run : `php artisan migrate`
- run : `php artisan serve`
