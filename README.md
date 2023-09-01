# DB Examples

Repositorio construido para fines pedagógicos. Contiene diversos ejemplos de las principales bases de datos de la actualidad, tanto relacionales como no relacionales.

## FAQ

### ¿Cómo Utilizarlo?

Crear archivo llamado **.env** en la raíz del proyecto con la configuración de las variables de entorno que requiere Docker. Las variables se encuentran definidas en el archivo **.env.example**

### ¿Cómo crear una instancia de una base de datos en mi sistema?

```shell
## para Postgres
docker compose up -d postgres

## para SQL Server
docker compose up -d mssql

## para MongoDB
docker compose up -d mongodb

## para Cassandra
docker compose up -d cassandra

## para Redis
docker compose up -d redis
```
