# 作業メモ

## Laravel install
composer create-project laravel/laravel your_project_name --prefer-dist "9.*"

## 所有者:グループの変更
chown -R myusername:mygroupname your_project_name

## 権限変更
chmod -R 777 storage

## Breeze install
composer require laravel/breeze --dev<br>
php artisan breeze:install<br>
npm install<br>
npm run dev<br>
.env edit
php artisan migrate<br>
npm run build<br>

## Add locales
composer require laravel-lang/publisher laravel-lang/lang --dev
php artisan lang:add ja
edit config/app.php
## Update locales
php artisan lang:update

## 参考資料
https://readouble.com/laravel/9.x/ja/releases.html<br>
https://publisher.laravel-lang.com/