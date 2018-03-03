# Laravel Practice

## What is, How does it work
- why composer
- composer
- write plain `php` to see how composer works
- autoloading files
- Git manage like what is to `.gitignore`

## Install
- via `composer` in  `global` or `local`
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

- `php artisan key:generate`

## Developing Environtments
- local
- Homestead
- preparing database with homestead
- preparing database with local
## Model
- `php artisan make:model` , and parameters
- fillable
- attributes
- scope
- slug `using existing package`
- relation
- getdata
- pagination

## Views
- passing data
- using composer view 

## Controller
- `php artisan make:controller` , and parameters
- add midleware
- resource

## Query Buliders
- scope
- eager load
- pagination
- find
- get
- first
## Routing
- wild card
- namespace
- as
- group
- prefix
- middleware | permission
- list
- resouce
- set names
- get
- post
- put
- delete

## Migration
- `php artisan make:migration` , and parameters
- faker
- seeder

## Auth Scaffolding 
* Generate Auth
- `php artisan make:auth`
- `php artisan migrate --seed`
- how auth works behiind `framework`



## CRUD
- crud `create, read, update, delete`
- validations
- manage Request

## Relationships
- set relation through `models`
- query Bilder

## Authentications
- middlewares
## Validation
- through `Request` class
- through local `controller`

## Rules
- custome rules

## Middleware
- on routes
- on controllers
- custome middleware

## Notificatons
- through `email`
- through `database`

## Policy
- registering to `provider`

## Events / Listeners
- registering to `provider`
- creating `events` then add `listener`

## Email

## Managing Codes
- using `traits`
- using `repository`

## Tinker
- `php artisan tinker`

## Unit Testing with PHPUnit
- setting up test `classes`
- setting up test `methods`
- assertion types
- test with `laravel` in `laravel-browser-kit`
- test with plain `php`
- beautiful print

## Custome Console with Artisan Command
- registering to `kernel`

## Packagist
- dependencies
- install
- autoloader
- except autoload
- make our own

## xDebug
