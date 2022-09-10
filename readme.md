# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Use docker-compose up to in the cloned directory to run the backend/frontend and mongodb.
2. If you run these containers on a remote host like me, remember to modify the docker-compose.yml line 28. Replace the `localhost` with your remote machine's IP or hostname.