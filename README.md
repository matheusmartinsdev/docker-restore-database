# docker-restore-database
A simple shell script to drop and restore a postgresql database running in a container

The main propourse of the script is restore a PostgreSQL database inside a docker container.

## Installation

Just download the resdb file, give to him execution privileges and put this inside your /usr/bin folder.

```
$ cd /path/to/resdb/file
$ sudo chmod +x ./resdb
$ sudo mv ./resdb /usr/bin/resdb
```

## Usage

```
resdb [docker-container-name] [postgres-user] [database-name] [pgbkp-filename]

docker-container-name: the name of your docker container
postgres-user: the username in postgresql
database-name: database name
pgbkp-filename: .pgbkp file to be restored inside your database
```
