# UltimateFeed-API /UF-API /

Repository for the main backend api in the UF project.

## Getting started

```bash
# 1. Clone this repository.

# 2. Enter your newly-cloned folder.
$ cd my-nest-app

# 3. Create Environment variables file.
$ cp .env.example .env
```

## Installation

```bash
npm install
```

## Database

The project uses PostgresSQL as a database

### Configuration

fill correct configuration in env file

```env
DB_HOST=localhost
DB_PORT=5432
DB_USERNAME=postgres
DB_PASSWORD=postgres
DB_DATABASE=aiom
```

### Migrations

```bash
# To create new migration file
$ npm run migration:create migration_name

# Truncate full database (note: it isn't deleting the database)
$ npm run schema:drop

# Generate migration from update of entities
$ npm run migration:generate migration_name
```

## Running the app

```bash
# build
$ npm run build

# watch mode
$ npm run start:dev

# debug mode
$ npm run start:debug

# production mode
$ npm run start:prod
```

## Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```
