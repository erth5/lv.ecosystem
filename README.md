# lv.ecosystem
Collection on Addons they can be installed in Laravel Projects

over 8000 ProjectFiles + 40.000 vendor, so create it local itself:

````
composer create-project laravel/<name>
````

posssible addons:
* breeze
* cashier
* horizon
* jetstream
* octane
* socialite
* telescope
* valet
* sanctum

For Simples, I have entered the following into the terminal:

````
composer create-project laravel/breeze
composer create-project laravel/cashier
composer create-project laravel/horizon
composer create-project laravel/jetstream
composer create-project laravel/octane
composer create-project laravel/socialite
composer create-project laravel/telescope
composer create-project laravel/valet
composer create-project laravel/sanctum
````

only dependencies:
````
mkdir <name> && cd <name>

composer require livewire/livewire
````

,but ALL Addons must be installed in a previously created Laravel-Project to be functionable !


**Breeze** provides a minimal and simple starting point for building a Laravel application with **authentication**.

Laravel **Cashier** Stripe provides an expressive, fluent interface to Stripe's subscription **billing services**.

Laravel **Horizon** provides a beautiful **dashboard** and code-driven configuration for your Laravel powered Redis queues. Horizon allows you to easily monitor key metrics of your queue system such as job throughput, runtime, and job failures.

Laravel **Octane** supercharges your application's performance by serving your application using high-powered application servers, including Open Swoole, Swoole, and RoadRunner. Octane boots your application once, keeps it in **memory**, and then feeds it requests at supersonic speeds.

socialite: OAuth

telescope: monitoring

valet: development environment for macOS

sanctum: authentication system for SPAs (single page applications), mobile, token based APIs