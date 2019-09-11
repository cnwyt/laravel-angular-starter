# laravel-angular-starter

laravel5.8 &amp; angular8.2



directory structure

```sh
- /laravel/           backend api code
   ├── app/
   ├── artisan
   ├── bootstrap/
   ├── composer.json
   ├── composer.lock
   ├── config/
   ├── database/
   ├── package.json
   ├── phpunit.xml
   ├── public/
   ├── resources/
   ├── routes/
   ├── server.php
   ├── storage/
   ├── tests/
   ├── vendor/
   ├── webpack.mix.js
   └── yarn.lock
- /angular-client/   frontend code
   ├── README.md
   ├── angular.json
   ├── browserslist
   ├── e2e/
   ├── karma.conf.js
   ├── node_modules/
   ├── package-lock.json
   ├── package.json
   ├── src/
   ├── tsconfig.app.json
   ├── tsconfig.json
   ├── tsconfig.spec.json
   └── tslint.json
```


## Install

```sh
$ git clone git@github.com:cnwyt/laravel-angular-starter.git
```

laravel: 

```sh
$ cd laravel && composer install

$ cp .env.example .env
$ php artisan key:generate
```


angular: 

```sh
$ cd ../

$ cd angular-client && npm install
```


