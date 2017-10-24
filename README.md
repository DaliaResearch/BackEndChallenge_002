# Spock vs Lizard Game

Interview challenge for Dalia Research

## General Stack

- Rails 5+
- Ruby 2.4+
- Postgres 9+

## Setup

- Make sure Ruby is installed in version 2.4 or higher
- Create the postgres user with proper permissions (see config/database.yml)
- Make sure you have a `.env` with the proper credentials (see below)
- Run `bundle install`
- Create dev DB: `$ rake db:create db:migrate`

Run `rails s` to start a local server on http://localhost:3000

## Tests

- Get the latest geckodrive from https://github.com/mozilla/geckodriver/releases
- Create test DB: `$ RAILS_ENV=test rake db:create db:migrate`
- Run `rspec` to run the tests

## ENV Variables

SPOCK_VS_LIZARD_DATABASE_PASSWORD: Database password