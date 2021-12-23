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
