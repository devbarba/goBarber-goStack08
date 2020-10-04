# goBarber-goStack08

A simple app to manage, and perform beard and haircut appointments for a barber shop.

# Requirements

Database Postgres
Install with docker

```shell
docker run --name postgres -e POSTGRES_PASSWORD=docker -p 5432:5432 -d postgres
```

# Dependencies

```shell
yarn install
```

# Migrations

```shell
npx sequelize db:migrate
```

# Test

```shell
yarn dev
```
