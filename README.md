docker-postgresql
=================

PostgreSQL with PostGIS2 (from the UbuntuGIS stable repository). Forked from orchardup/docker-postgresql

    $ docker run -d -p 5432:5432 -e POSTGRESQL_USER=test -e POSTGRESQL_PASS=oe9jaacZLbR9pN -e POSTGRESQL_DB=test jochem/postgresql91-postgis2
    da809981545f
    $ psql -h localhost -U test test
    Password for user test:
    psql (9.1.9, server 9.1.3)
    Type "help" for help.

    test=#

(Example assumes PostgreSQL client is installed on Docker host.)

