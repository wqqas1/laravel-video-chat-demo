# laravel-video-chat-demo
Laravel Video Chat using Socket.IO and WebRTC ( Demo )

Install the JavaScript dependencies:

```javascript
    npm install
    npm install --save laravel-echo js-cookie vue-timeago socket.io socket.io-client webrtc-adapter vue-chat-scroll
    laravel-echo-server init
```
To start laravel-echo-server
````javascript
    laravel-echo-server start
````

```php
    cp .env.example .env
    composer install
    php artisan key:generate
    php artisan migrate --seed
    php artisan storage:link
```
change APP_URL in .env
change BROADCAST_DRIVER=redis in .env
Uncomment App\Providers\BroadcastServiceProvider in the providers array of your config/app.php configuration file
If you are running the Socket.IO server on the same domain as your web application, you may access the client library like

```javascript
<script src="//{{ Request::getHost() }}:6001/socket.io/socket.io.js"></script>
```

Finally, you will need to run a compatible Socket.IO server. Use tlaverdure/laravel-echo-server GitHub repository.

[laravel-video-chat](https://github.com/Wqqas1/laravel-video-chat)


This whole work is based on https://github.com/PHPJunior/laravel-video-chat but modified to make it compatible with laravel 5.7 this version does not work with laravel versions less than 5.7 for that you can download the original package