


Installation :

- `composer install`
-  Créer un .env à partir du .env.example comme modèle (copier-coller)
- `php artisan key:generate`
- `php artisan storage:link`
-  Créer une base de donnée à l'aide de Mysql
-  Faire un `php artisan migrate`
-  Faites un `USE <nom de la DATABASE>` dans MYSQL
-  Récuperer les informations "recipes" et "popings" du fichier create_recipes.sql et copier les en cli

Lancement du site :

- `php artisan serve`
