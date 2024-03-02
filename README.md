## Data base UP

```
docker-compose up -d
```

## Data base DOWN

```
docker-compose down
```

## Data base connection whit terminal 

```
psql -h 127.0.0.1 -U root -W cj-db
```

## Comandos básicos:

* \q: Salir de psql.
* \l: Listar las bases de datos disponibles.
* \c <nombre_de_la_base_de_datos>: Conectarse a una base de datos específica.
* \? Help
* SELECT * FROM <nombre_de_la_tabla>; Mostrar todos los datos de una tabla.
* HELP: Mostrar ayuda sobre los comandos de psql.
