## How to use for the first time
- ``` git clone ```
- 

## How to use shield plugin for resource
- create model and migration for resource, then do artisan migrate
- then create resource with make:filament-resource ModelNameResource --genereate
- php artisan shield:generate --resource=ModelNameResource -> this will create Policy for this model and add default permissions to database