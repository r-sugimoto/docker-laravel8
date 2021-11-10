# DockerでLaravel8環境構築

## Docker立ち上げ
docker-compose up -d

## サーバーに入る
docker-compose exec app bash

## Laravel構築
composer create-project laravel/laravel [プロジェクト名] "8.*"

## default.confの「*****」をプロジェクト名に合わせる

## .envなど修正

## Laravel
http://localhost:8000/

## phpMyAdmin
http://localhost:8080/

## DB情報は「docker-compose.yml」を確認する

## Composerエラーの解決策
composer diag<br>
でエラーの内容を確認する

## 認証設定
composer require laravel/breeze --dev

php artisan breeze:install<br>
or<br>
php artisan breeze:install vue<br>
or<br>
php artisan breeze:install react<br>

## npm install
npm install

## npm run dev
npm run dev

# 補足

## LaravelでFormを使う
composer require laravelcollective/html
