# KNEX-reminders
A list of helpful reminders when creating an API with knex.


## Starting Out
`npx kinex init` Creates a knexfile.js
REMEMBER: add `useNullAsDefault: true` to the development dependency of the knex file

## Making a Migration
`npx knex migrate:make filenamegoeshere` to create a new table
`npx knex migrate:rollback` use this whenever you edit any migration
`npx knex migrate:latest` use this to deploy a new migration or after making changes

## Making Seeds
`npx knex seed: make 001-yournamehere` to create a new seed
REMEMBER TO INCREMENT THE THREE-DIGIT INTEGER BY 1 FOR EVERY NEW SEED
`npx knex seed:run` to start up the new seeds
