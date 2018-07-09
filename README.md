## Pasos iniciales al momento de crear proyecto con react y Laravel

php artisan preset react

npm install

npm run watch

php artisan make:auth
pph artisan migrate

Error in configure database

'charset' => 'utf8mb4',
'collation' => 'utf8mb4_unicode_ci',
to

'charset' => 'utf8',
'collation' => 'utf8_unicode_ci',


php artisan make:model Task -m

php artisan make:controller TaskController --resource
