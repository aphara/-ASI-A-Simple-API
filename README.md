# ASI - A Simple API

This is a simple Restful API for the ASI class project.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Installing

To run this API you need to install [Composer](https://symfony.com/doc/current/setup/composer.html) then [Symfony](https://symfony.com/doc/current/setup.html).  

Then go to the root folder of this API and start the server :

```shell
cd my-project
symfony server:start
```

OR use the php command

```shell
php bin/console server:start
```

If you're using a VM, you may need to tell the server to bind to all IP addresses:

```shell
 php bin/console server:start 0.0.0.0:8000
```

Open your browser and navigate to <http://localhost:8000/>. If everything is working,
you'll see a welcome page.

## Running the tests

You can test this API with [Postman](https://www.getpostman.com/products).

The routes can be tested as follow example :

```
GET localhost:8000/api/users/
```

```
[POSTMAN COMMAND] localhost:8000/api/[entities]/
```

## Built With

* [Symfony](https://symfony.com/) - The PHP framework used
* [API Platform](https://api-platform.com/) - Dependency Management
* [Postman](https://www.getpostman.com/products) - Used to test the API

## Authors

* **Alexandre Pharamond** - *Initial work* - [aphara](https://github.com/aphara)
* **Sébastien Quillet** - *Initial work* - [sebquil](https://github.com/sebquil)

## Acknowledgments

* [Symfony with API Platform tutorial](https://www.nielsvandermolen.com/symfony-4-api-platform-application/) - Niels van der Molen