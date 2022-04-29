

<!-- title -->
<h1 align="center">Curso - ServerWebSocket</h1>
<!-- end title -->

<!-- commit name -->
### Commit | __Agregando, configurando y usando tu propio servidor de WebSockets__
<!-- end commit name -->

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

<!-- official documentation -->
[Documentación oficial | `Laravel 6.*` ](https://laravel.com/docs/6.x)
[Documentación oficial | `Laravel Web Sockets.*` ](https://beyondco.de/docs/laravel-websockets/getting-started/introduction)
<!-- end official documentation -->

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

<!-- commit instructions -->
#### Instrucciones Commit
- Instalar WebSocket
  > composer require beyondcode/laravel-websockets
  - Instalar
    > php artisan vendor:publish
    - Elegir el número asociado a la opción `BeyondCode\LaravelWebSockets\WebSocketsServiceProvider`
- Ejecutar las migraciones
  > php artisan migrate
- Ejecutar el servidor de websocket como prueba
  > php artisan websocket:serve
- Ver las estadísticas de Websocketes
  - Correr el servidor de websockets
    > php artisan websocket:serve
  - Correr el servidor de Artisan
    > php artisan serve --port 81
<!-- end commit instructions -->

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

<!-- notes -->
#### Notas:
<!-- end notes -->

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

<!-- information -->
#### Información:
- Más información en `config\websockets.php`
<!-- end information -->