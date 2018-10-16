# laravel-video-chat-demo
Laravel Video Chat using Socket.IO and WebRTC ( Demo )

Install the JavaScript dependencies:

```javascript
    npm install
    npm install --save laravel-echo js-cookie vue-timeago socket.io socket.io-client webrtc-adapter vue-chat-scroll
    laravel-echo-server init
```

```php
    cp .env.example .env
    composer install
    php artisan key:generate
    php artisan migrate --seed
```

[laravel-video-chat](https://github.com/Wqqas1/laravel-video-chat)


This whole work is based on https://github.com/PHPJunior/laravel-video-chat but modified to make it compatible with laravel 5.7 this version does not work with laravel versions less than 5.7 for that you can download the original package