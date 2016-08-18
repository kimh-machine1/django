# canary-django

[![CircleCI](https://circleci.com/gh/circleci/canary-django.svg?style=svg&circle-token=aeaf9bc3eaeabe7a1af28193253a198e6b0c1078)](https://circleci.com/gh/circleci/canary-django)

This Django app builds and runs various tests:

- unit tests for database models
- functional tests with Selenium



## TODO

- more tests
- all-auth and logging in... use mailhog for email testing
- Cron Jobs
- add parallelization
- deploy to Heroku
- test with multiple python versions
- run with coverage on CircleCI
- add coverage badge to readme
- make email testing work locally (? mailhog ?)
- make email testing work on CircleCI