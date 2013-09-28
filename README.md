# Torquebox-Demo

## Installation

Requires mysql database. Install dependencies with bundler, and create/migrate database schema with rake tasks:

```
$ bundle install
$ rake db:create
$ rake db:migrate
```

## Deployment

```
$ RAILS_ENV=production rake db:create
$ RAILS_ENV=production rake db:migrate
$ RAILS_ENV=production rake assets:precompile
$ warble executable war
$ java -jar torquebox-demo.war
```