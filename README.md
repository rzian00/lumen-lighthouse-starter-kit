# Lumen Lighthouse Starter Kit

Lumen integrated with lighthouse for using Graphql.

## Installation

In your command line write as follows:

> *Clone the repo*
```
git clone https://github.com/rzian00/lumen-lighthouse-starter-kit.git lumen-lighthouse-api
```

> *Change directory and install vendors*
```
cd lumen-lighthouse-api && composer install
```

> *Generate Homestead.yaml for your vagrant and make sure you configure it*
```
php vendor/bin/homestead make
```

> *Run your vagrant environment*
```
vagrant up
```

> (Optional): *Once vagrant is running migrate your database tables*
```
php artisan migrate
```

> (Optional): *after migration completed you can seed user data as I have already prepared for you just run code below*
```
php artisan db:seed
```

End of installation have fun!

## Usage

Check your [localhost](http://homestead.test/graphql-playground) and make sure your vagrant is running.

## Credits

#### Lumen Official Documentation

Documentation for the framework can be found on the [Lumen website](https://lumen.laravel.com/docs).

#### Lighthouse Official Documentation

Documentation for the framework can be found on the [Lighthouse website](https://lighthouse-php.com/master/getting-started/installation.html).
