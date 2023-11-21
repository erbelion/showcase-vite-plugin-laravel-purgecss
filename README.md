# tutorial-vite-plugin-laravel-purgecss

tutorial for [@erbelion/vite-plugin-laravel-purgecss](https://github.com/Erbelion/vite-plugin-laravel-purgecss)@0.2.3 running on laravel/laravel@10.2.9

## how to run this example

clone this repo

```
composer install
npm install
npm run build
php artisan serve
```

## how to do it yourself

```
cd tutorial-vite-plugin-laravel-purgecss
composer create-project laravel/laravel:10.2.9 .
composer require laravel/ui
php artisan ui bootstrap
npm install @erbelion/vite-plugin-laravel-purgecss@0.2.3
npm run build
php artisan serve
```

changed [resources\views\welcome.blade.php](https://github.com/erbelion/tutorial-vite-plugin-laravel-purgecss/blob/main/resources/views/welcome.blade.php)

changed [vite.config.js](https://github.com/erbelion/tutorial-vite-plugin-laravel-purgecss/blob/main/vite.config.js)

added but not needed [public\guide.png](https://github.com/erbelion/tutorial-vite-plugin-laravel-purgecss/blob/main/public/guide.png)

## results

### laravel
```
public/build/assets/app-041e359a.css  225.70 kB │ gzip: 30.76 kB
```

### laravel + @erbelion/vite-plugin-laravel-purgecss
```
public/build/assets/app-041e359a.css    9.64 kB │ gzip:  2.86 kB
```
