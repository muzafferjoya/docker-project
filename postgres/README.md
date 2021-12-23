## start docker container
```sh
docker-compose up
```

## connect to th database container
```sh
docker-compose run database bash
```

## inside psql

```sh
psql --host=database --username=khan --dbname=test
```

## create table and assign values
```sh
\d
CREATE TABLE color_table(name TEXT);
\d
SELECT * FROM color_table;
INSERT INTO color_table VALUES ('blue');
SELECT * FROM color_table;
```
