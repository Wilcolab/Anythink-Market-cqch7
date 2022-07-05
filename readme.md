# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

When first setting up your environment, we need to ensure that we have the following components installed:
- [Docker](https://docs.docker.com/get-docker/)

My suggestion is to also install Microsoft's VSCode, which will make development much easier. This can be acquired [here](https://code.visualstudio.com/download).

Upon installing Docker for the first time, especially on Windows, you will need to either logout or reboot to complete the installation. Please do so, and then continue this setup. To verify Docker is installed and running, please run these commands
`docker -v` and `docker-compose -v`. Once you have verified that both of these commands work and return code, you may start the container. In order to do so:
- In a terminal, run `docker-compose up` **from the project root directory**