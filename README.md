# SaveSailor

Project for Tampere Universities: COMP.SE.610/620 _ Spring 2022 _ Software Engineering Project 1 &amp; 2

## Installation

### Secrets

Rename `empty_secrets.env` to `secrets.env` and add values to keys

### Required packages

- docker
- docker-compose

### Building

Clone the repository and build containers

    git clone https://github.com/kakkurij/SaveSailor.git SaveSailor
    cd SaveSailor
    docker-compose build

## Usage

### Starting database

    docker-compose up database

### Running tests

This starts the database and runs tests

    docker-compose run tests
