# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

- Make sure you have Docker Desktop installed. You can follow the instructions [here](https://docs.docker.com/get-docker/)
- You can verify docker is ready by running the following commands in your terminal: `docker -v` and `docker-compose -v`
- Clone this repository by running the follow command `git clone git@github.com:ObelusFamily/Anythink-Market-kydog.git`
- Next start the Docker containers by navigating to the repository root and running `docker-compose up`
- Once that has completed, you can test that your containers are working by visiting [http://localhost:3000/api/ping](http://localhost:3000/api/ping) and [http://localhost:3001/](http://localhost:3001/)  
