<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>



## About Laravel Version 11

### Installation

`````
composer global require laravel/installer
laravel new laravel-V11 --dev 
````````

#### 1. Configuration
All configuration files now have framework counterparts and application level configuration is merged with the framework defaults. The default configuration files have also received many more environment variables so that more options can be changed from the application’s `````.env````` file. The LoadConfiguration bootstrap class has been added to support framework configuration cascading. A new ``````php artisan config:publish`````` command has been introduced to publish framework configuration files.

- No files inside config i.e app.php etc

#### Installers
