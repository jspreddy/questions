

## About Questions

Questions is a an application to ask questions and get answers and also vote for the questions and answers.

It is a baby form of `StackOverflow`.

Building this application to explore and learn `Laravel`.

## Runs in Docker

Runs in a docker compose environment on images:

- `bitnami/laravel`
- `bitnami/mariadb`

## Running it


```
$> docker-compose up
```

## Running artisan commands

```
$> docker-compose exec questions php artisan
```

## Warning

The database is a fresh version built from the migrations everytime we run the application.

## License

Propreitary. For now. Not available to the world.
