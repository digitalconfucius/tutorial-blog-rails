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

## Render (free) deployment

https://docs.render.com/deploy-rails

See `./bin/render-build.sh` and `render.yaml`

View live (takes ~1 minute to spin up free tier): https://tutorial-blog.onrender.com/articles

