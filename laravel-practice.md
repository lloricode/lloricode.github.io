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
# Model
- `php artisan make:model` , and parameters
- fillable
- attributes
- scope
- slug `using existing package`
- relation
- getdata
- pagination

# Views
- passing data
- using composer view 
# Controller
- `php artisan make:controller` , and parameters
- add midleware
- 
# Migration
- `php artisan make:migration` , and parameters
- 

# Auth Scaffolding 
* Generate Auth
- `php artisan make:auth`
- `php artisan migrate --seed`



# CRUD
- crud `create, read, update, delete`
- validations

# Relationships
- set relation through `models`
- Query Bilder

# Authentications
- middlewares


