# Mariadb

## About

This Acorn provides a MariaDB database through the Acorn service interface. You can use this Acorn to create a database for your application during development. This launches a single MariaDB container backed by a persistent volume.

The usename and passwords for the `root` and `db_user` are randomly generated and stored in the Acorn's secret. The `db_user` is granted all privileges on the database created at startup.
