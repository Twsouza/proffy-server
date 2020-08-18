# Proffy Server

This is an API used by ReactJS and ReactNative.
It is done using Typescript, Express and Knex (for connection to the database).
The database is stored in the `src/database/database.sqlite` file

## Configuration

To create the bank and its structure, run the command:
```
yarn knex: migrate
```

## Start the application - development

To start in development, run:
```
yarn knex: migrate
```

# Endpoints

## Connections

- Route to list all connections made through proffy;
- Route to create a new connection

## Classes

- Route to list teachers;
 - It must be possible to filter by subject, day of week and time;
