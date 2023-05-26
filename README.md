# Laravel Livewire sample

By [Material Dashboard 2 Laravel Livewire](https://material-dashboard-laravel-livewire.creative-tim.com).

![version](https://img.shields.io/badge/version-1.0.0-blue.svg) 
![license](https://img.shields.io/badge/license-MIT-blue.svg)
[![GitHub issues open](https://img.shields.io/github/issues/creativetimofficial/material-dashboard-laravel-livewire.svg)](https://github.com/creativetimofficial/material-dashboard-laravel-livewire/issues?q=is%3Aopen+is%3Aissue) 
[![GitHub issues closed](https://img.shields.io/github/issues-closed-raw/creativetimofficial/material-dashboard-laravel-livewire.svg)](https://github.com/creativetimofficial/material-dashboard-laravel-livewire/issues?q=is%3Aissue+is%3Aclosed)


*Frontend version*: Material Dashboard v3.0.0. More info at https://www.creative-tim.com/product/material-dashboard.


## Prerequisites

If you don't already have an Apache local environment with PHP and MySQL, use one of the following links:

 - Windows: https://updivision.com/blog/post/beginner-s-guide-to-setting-up-your-local-development-environment-on-windows
 - Linux: https://howtoubuntu.org/how-to-install-lamp-on-ubuntu
 - Mac: https://wpshout.com/quick-guides/how-to-install-mamp-on-your-mac/

Also, you will need to install Composer: https://getcomposer.org/doc/00-intro.md   
And Laravel: https://laravel.com/docs/9.x/installation

## Installation

1. Unzip the downloaded archive
2. Copy and paste **material-dashboard-2-free-livewire-master** folder in your **projects** folder. Rename the folder to your project's name
3. In your terminal run `composer install`
4. Copy `.env.example` to `.env` and updated the configurations (mainly the database configuration)
5. In your terminal run `php artisan key:generate`
6. Run `php artisan migrate --seed` to create the database tables and seed the roles and users tables
7. Run `php artisan storage:link` to create the storage symlink (if you are using **Vagrant** with **Homestead** for development, remember to ssh into your virtual machine and run the command from there).

## Licensing

- Copyright 2022 [Creative Tim](https://www.creative-tim.com?ref=readme-md2ll)
- Creative Tim [license](https://www.creative-tim.com/license?ref=readme-md2ll)

## Credits

- [Creative Tim](https://creative-tim.com/?ref=md2ll-readme)
- [UPDIVISION](https://updivision.com)
