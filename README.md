# Install and Set Up Laravel with Docker Compose

Configurando o Laravel no ambiente local com Docker que inclui: Nginx, PGSQL, PHP e pgadmin.

## Como usar o PostgreSQL como banco de dados

1. Uncomment the PostgreSQL configuration inside the ```docker-compose.yml``` including: ```db``` and ```pgamdin```
2. Copie ```.env.example``` to ```.env```
3. Altere ```DB_CONNECTION``` to ```pgsql```
4. Altere ```DB_PORT``` to ```5432```
5. Abra o ```pgAdmin``` on ```127.0.0.1:5050```

## Como executar os comandos Laravel com o Docker Compose 

1. ```cd src```
2. ```docker-compose exec app php artisan {Seu comando}``` 
