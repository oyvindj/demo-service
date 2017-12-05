# demo-service Java / Springboot service

Requires MongoDB and Java 1.8

## Installation

``` bash
# install Mongo DB on Mac
brew install mongodb

# run Mongo DB
mongod

# run Mongo DB client
mongo

# show databases
show dbs

# show collections (tables) in current database
show collections

# show all rows in table (table name is class name in lowercase)
db.TABLENAME.find()
```

The default database when starting the client is test. This is also the default database used by Spring.

## Development
The service project must run on a different port than the frontend project
```
# application.properties
server.port = 8081
```
