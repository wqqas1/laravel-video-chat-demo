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
