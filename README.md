
# E-commerce Project - Fashion Shop

The Fashion Shop - A Laravel Fashion Shop Website Project is an open source ecommerce/online shop management system using Laravel.


## Features

- User Authentication
- Full featured shopping cart
- Product reviews
- Filterable products
- Product search feature
- User profile with wishlist and orders
- Admin product management
- Admin user management
- Admin order details page
- Order products to deliever state
- Checkout process
- Visa card integration
- Mail system


## Installation Instructions

- Clone the repo
- Run `composer install`
- Run `php -r "file_exists('.env') || copy('.env.example', '.env');"`
- Run `php artisan key:generate --ansi`
- Create a database named `fashionshop` (or you can change the name in .env) in your localhost
- Edit `.env` file
- Run `npm install`
- Run `php artisan migrate --seed`
## Run Locally

Start the server

```bash
  php artisan serve
```


## Website

The website is hosted at http://bypiccolo.com/ .