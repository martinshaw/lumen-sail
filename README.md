# lumen-sail
Installing Laravel Sail Package in Lumen

composer require martinshaw/lumen-sail

Add this line to bootstrap/app.php

$app->register(martinshaw\LumenSail\LumenSailServiceProvider::class);

