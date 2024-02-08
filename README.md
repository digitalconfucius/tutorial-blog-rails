# README

Tutorial app.

## Postgres

`brew install postgresql` # first time install of pg

`brew services start postgresql`

`rails db:system:change --to=postgresql`

`bundle install`

`createuser -P -d digitalconfucius` # create user

`initdb /usr/local/var/postgresql@14 -E utf8` # init pg db

`pg_isready` # Verify ready

`bin/rails db:create`

`bin/rails db:migrate`

