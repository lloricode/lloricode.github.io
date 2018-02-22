# Install
- composer `composer create-project --prefer-dist laravel/laravel <project-folder-name>`
- serve `php artisan serve`
```
## if
Laravel development server started: <http://127.0.0.1:8000>
[Thu Feb 22 12:52:36 2018] Failed to listen on 127.0.0.1:8000 (reason: Address already in use)
```
- serve `php artisan serve --port <your-available-port>`
- .env `automatic with composer create-project`

*note when local serve*
- when updating `.env`, you need to stop `serving` by `ctrl + C`, then re-run it.

# Auth Scaffolding 
* Generate Auth
- `php artisan make:auth`
- `php artisan migrate --seed`




# Models, Views, Controllers,

-

# CRUD
- crud `create, read, update, delete`
- validations

# Relationships
- Query Bilder

# Authentications
- middlewares


