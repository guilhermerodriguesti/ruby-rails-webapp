# ruby-rails-webapp

## Pre-Requirements
First install `docker`, `docker compose` for your machine and start it. How this is done is very well documented all over the internet.

### Build the project
You need generate the Rails skeleton app using docker-compose run:
```
$ docker-compose run --no-deps webapp rails new . --force --database=postgresql --skip-git --webpack=react -T
```