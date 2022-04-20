<div align="left">
    <h3>Laravel Multi Language Template</h3>
	<sup>Last Updated At: 16.04.2022</sup>
    <hr/>
    <div>
        <small>This Laravel Multi-Language Template has latest version of Laravel and <a href="https://github.com/mcamara/laravel-localization">@mcamara/laravel-localization</a> with helper classes and futures.
    </div>
</div>

## Specifications
- Built-in Helpers directory for helper classes.
- LocalizationHelper for list middleware of Localization
- Example Multi-Language route in web.php
- Shows app current language in welcome view beside of PHP version.

## Install Instructions
Go to the project folder and copy .env.example as .env after that step same as generic Laravel Installation. You can find list of commands you need to execute below.

```bash
cd project-name
cp .env.example .env
php artisan key:generate
php artisan optimize:clear
```

## Test
If you want to see localizated routes please visit app.test/es app.test/en.
