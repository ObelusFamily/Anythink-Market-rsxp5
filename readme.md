# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

* Clone the repositary

```
git clone git@github.com:ObelusFamily/Anythink-Market-rsxp5.git webapp
cd webapp
```

* Run the Docker service

```
docker-compose up
```

* Visit the frontend via : `localhost:3001`. 

* You should be able to find the backend service via : `localhost:3000/api/ping`.

These have been auto-booted via nodemon.