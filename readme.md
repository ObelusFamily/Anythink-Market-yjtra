# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Before we dive into the code, we need Docker. It’s going to make it easier for us to run things locally, which we’ll have to do a lot during your work here.
So first thing’s first - install Docker.
Great! You can verify docker is ready by running the following commands in your terminal: docker -v and docker-compose -v.
Then, run docker-compose up from the project root directory to load Anythink's backend and frontend.
If docker is working correctly, the backend should be running and able to connect to your local database.
Let's test this by pointing your browser to http://localhost:3000/api/ping
Easy Peasy! The backend is up and running.
Now, it’s time to check the frontend and make sure it’s connected to the backend.
If everything is working properly, you’ll be able to create a new user on http://localhost:3001/register
Create one (choose a cool nickname and everything) and you’ll be able to move to the next task.

