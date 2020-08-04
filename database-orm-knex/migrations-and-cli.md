# Migrations and cli

## Knex migrations in "./migrations" folder.

## Install knex console "cli":

```bash
sudo npm i knex -g
```

## Create a empty knexfile.js

```bash
knex init
```

## Run the last migration

```bash
knex migrate:latest
```

## Create a new migration

```bash
knex migrate:make users
```

## Remove changes

```bash
knex migrate:rollback
```

