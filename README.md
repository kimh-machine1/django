# canary-django

[![CircleCI](https://circleci.com/gh/circleci/canary-django.svg?style=svg&circle-token=aeaf9bc3eaeabe7a1af28193253a198e6b0c1078)](https://circleci.com/gh/circleci/canary-django)

This Django app builds and runs various tests:

- unit tests for database models
- functional tests with Selenium

## Notes

- uses Python 3.5.1
- uses Django LTS Release (1.8.x)
- using [direnv](http://direnv.net/) locally to set environment variables
- using CircleCI project settings to set environment variables in testing

## TODO

- more tests
- add parallelization
- deploy to Heroku
- test with multiple python versions
- run with coverage on CircleCI
- add coverage badge to readme
- all-auth and logging in... use mailhog for email testing
- make email testing work locally (? mailhog ?)
- make email testing work on CircleCI