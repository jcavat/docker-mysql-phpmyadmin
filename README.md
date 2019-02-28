# docker-lamp

Docker example with  MySql 8.0 and PhpMyAdmin with docker-compose.

I provide a fake Conference database system.

## How to run

```
docker-compose up -d
```

Open phpmyadmin at [http://localhost:8000](http://localhost:8000)

You can use mysql inside the container :

- `docker ps` to extract the mysql container hash id 
- `docker exec -it hash_id_mysql bash`
- `mysql -u root -p` (use your password specified in docker-compose.yml)

Enjoy !
