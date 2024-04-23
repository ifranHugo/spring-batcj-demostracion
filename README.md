# Demo de Spring Batch

## Creacion del proyecto con Spring Boot Starter

## BD Docker usada en la demo
* Script docker para iniciar BD
```
docker run -it -p 3306:3306 -e TZ=America/Lima -e MYSQL_ROOT_PASSWORD=secreto -e MYSQL_DATABASE=batchdb -e MYSQL_USER=batch -e MYSQL_PASSWORD=secreto --name batchdb mysql:8.0.22 --character-set-server=latin1 --collation-server=latin1_general_ci

```


