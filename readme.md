1. Put sakila file into this dir
2. Put `.env` file in this dir
    1. change `.env` values if you would like
3. run following command: `docker-compose -f docker-compose.644-mysql.yaml up -d`
4. exec into container using `docker exec -it $CONTAINER-NAME bin/bash`
    1. `$CONTAINER-NAME` is something like `si644-db-1`
5. type `login`, which should be aliased to automatically log you into mysql shell
6. `sakila` database should be avaiable, test by running `SHOW DATABASES;`
7. once found, run `USE SAKILA;` and `SHOW TABLES;`
8. have fun, this should be a local latest mysql container

