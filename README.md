# Sistem Informasi Puskesmas
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

> Sistem Informasi Puskesmas adalah sebuah sistem berbasis web yang digunakan untuk membantu pasien Puskesmas Meo Meo berobat dan mendapatkan informasi dengan lebih mudah. Sistem ini dapat membantu pasien untuk mendapatkan informasi kontak dan jadwal tenaga kesehatan dan mempermudah pasien untuk mengantre secara daring.

## Development environment

* PHP v7.4.13
* Laravel v8.18.1
* MariaDB v10.4.17


## Install

Petunjuk instalasi dapat mengikuti [artikel berikut ini](https://devmarketer.io/learn/setup-laravel-project-cloned-github-com/).

```sh
composer install

npm install

cp .env.example .env

php artisan key:generate

php artisan migrate

php artisan db:seed
```

## Usage

```sh
php artisan serve
```

## Run tests

```sh
php artisan test
```
