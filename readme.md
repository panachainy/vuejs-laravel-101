# Vuejs-Laravel-101

## Prerequire

Install

```sh
brew update
brew install php
brew install composer
```

Verify

```sh
composer -V
```

## Initial project

### Prerequire init project

```sh
composer global require laravel/installer
```

### Command

#### Create project php

```sh
composer create-project --prefer-dist laravel/laravel blog
```

#### Install breeze

```sh
composer require laravel/breeze --dev
```

#### Apply Laravel Breeze

```sh
php artisan breeze:install

npm install
npm run dev
php artisan migrate
```

## Getting started

composer update

composer install

### Serve project

```sh
php artisan serve
```

### Migrate

```sh
php artisan migrate
```

## Ref

- https://stackoverflow.com/questions/51656914/how-to-install-composer-on-macos/51657423#51657423

- https://gist.github.com/shashankmehta/6ff13acd60f449eea6311cba4aae900a
