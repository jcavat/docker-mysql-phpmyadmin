# docker-lamp

Docker example with  MySql 8.0 and PhpMyAdmin with docker-compose.

I provide a fake Conference database system.

## How to run

```
docker-compose up -d
```

Open phpmyadmin at [http://localhost:8000](http://localhost:8000)

Run mysql client:

- `docker-compose exec db mysql -u root -p` 

Enjoy !
