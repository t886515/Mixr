# Mixr

Tinder for drinks

## Database setup

#### Open Postgres and create DB

* `psql postgres`
* `CREATE DATABASE mixr;`

#### Create tables

* `cd server/database` Go to database directory
* `sequelize init:config` Edit config with your db values
* `sequelize db:migrate` Create actual tables
