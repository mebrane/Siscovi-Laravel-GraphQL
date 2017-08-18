# Siscovi Laravel/GraphQL

#### Dependencies:
* [Laravel 5.x](https://github.com/laravel/laravel)
* [barryvdh/laravel-cors](https://github.com/barryvdh/laravel-cors)
* [rebing/graphql-laravel](https://github.com/rebing/graphql-laravel)
* [tymon/jwt-auth](https://github.com/tymondesigns/jwt-auth)
* [noh4ck/graphiql](https://github.com/noh4ck/laravel-graphiql)


#### Setup Composer.json:

**1-** Require the package via Composer in your `composer.json`.
```json
{
  "require": {
     "barryvdh/laravel-cors": "^0.9.2",
     "noh4ck/graphiql": "@dev",
     "rebing/graphql-laravel": "~1.4",
     "tymon/jwt-auth": "0.5.*"
  },
  "repositories": [
      {
          "url": "https://github.com/mebrane/Siscovi-Laravel-GraphQL"
      }
  ]
}
```

**2-** Run Composer to install or update the new requirement.

```bash
$ composer install
```

**3-** Create file  `.env` and  setting database in `.env`
 
**4-** Run artisan migrate and seeder

 ```bash
 $ php artisan migrate
 $ php artisan db:seed
 ```
 
**5-** Run application

```bash
 $ php artisan serve
 ```
 
 GraphQL : [http://127.0.0.1:8000/graphql/query](http://127.0.0.1:8000/graphql/query)

 GraphQL Ui : [http://127.0.0.1:8000/graphql-ui](http://127.0.0.1:8000/graphql-ui)