# laravel-material-design-mdc

Laravel 7 Template on Material Design Components 5.1.0([material.io](https://material.io/)) with user authentication and registration with email confirmation.(php artisan ui type --auth) Try it on: http://laravel-materal-design-template-with-mdc.sergiobogatsky.com

![](storage/app/public/captura-welcome.PNG)

All changes made inside

resources/js/app.js

resources/sass/app.scss,

resources/views

All the installation of php classes and controllers made by command *php artisan ui type --auth*  

## Installation

* clone the project
 ```bash
  git clone 
  ```
* Generate app key
 ```bash
 php artisan key:generate
 ``` 
* run composer to install php dependencies
 ```bash
  composer install
  ``` 
* run npm to install javascript and css dependencies
 ```bash
  npm install
  ``` 
* Create the database and put it name inside .env file

* finally run artisan to install the database
 ```bash
  php artisan migrate
  ``` 
## screenshots
![](storage/app/public/captura-login.PNG)

![](storage/app/public/captura-register.PNG)

![](storage/app/public/captura-error.PNG)
## License
[MIT](https://choosealicense.com/licenses/mit/)
