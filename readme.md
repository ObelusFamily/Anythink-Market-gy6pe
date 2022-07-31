# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup


- Install [Docker](https://docs.docker.com/get-docker/) by following instructions for your hardware.
- Once installed and started type the follwing in a terminal: `docker -v && docker-compose -v`
- Start all containers with `docker-compose up` and wait for the command to finish, this might take a while in the mean time we invite you to read the documentation of the [`up` command](https://docs.docker.com/engine/reference/commandline/compose_up/)
- Go to http://localhost:3000/api/ping, it'll do a minimal check that everything is in order - if you do not get a response reach out to someone in your Team for help
- Go to http://localhost:3001/register, create a user and you're done!

