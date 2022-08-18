# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## Local setup

### Clone repository

```sh
git clone https://github.com/ObelusFamily/Anythink-Market-1m635.git
# Or
gh repo clone ObelusFamily/Anythink-Market-1m635
```

### Docker

[Install docker.](https://docs.docker.com/get-docker/)

Verify that `docker` and `docker compose` are installed.

```sh
docker --version
docker compose version
```

### Launch project

```sh
# Run docker compose from the project root directory.
docker compose up
```

Ensure the backend is running and able to connect to the local database by pointing a browser to http://localhost:3000/api/ping.

Ensure the frontend is running and connected to the backend by creating a new user on http://localhost:3001/register.
