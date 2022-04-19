
# CRM FILE MANAGER

## Stack:
* nestjs
* docker-compose
* typeorm

## Installation

Copy env:
```bash
$ cp development.env .env
```

Install packages:
```bash
$ npm install
```

## Running the db

Run docker image db with deamon:

```bash
$ docker-compose up -d
```
Down docker container: 

```bash
$ docker-compose down
```

OPTIONAL. Run docker image db without deamon:

```bash
$ docker-compose up
```

## Running the app

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

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