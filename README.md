# Desafios Docker - DevOps Pro

Desafio 01 - Banco de Dados PostgreSQL
```
docker run -p 5432:5432 --name postgres -e POSTGRES_DB=curso_docker -e POSTGRES_USER=docker_usr -e P
OSTGRES_PASSWORD=docker_pwd -d postgres
```

Desafio 02 - Banco de Dados MySQL
```
docker run -d -p 3306:3306 --name mysql -e MYSQL_ROOT_PASSWORD="root" -e MYSQL_DATABASE="docker_db"
-e MYSQL_USER="docker_usr" -e MYSQL_PASSWORD="docker_pwd" mysql:latest
```

Desafio 03 - Banco de Dados MongoDB
```
docker run -d -p 27017:27017 --name mongo \
        -e MONGO_INITDB_ROOT_USERNAME=mongo_usr \
        -e MONGO_INITDB_ROOT_PASSWORD=mongo_pwd \
        mongo
```
