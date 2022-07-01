# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1) Install Docker in your machine - https://docs.docker.com/get-docker/
2) Verify The Docker Installation by running the following commands in the terminal :- 
            a) docker -v
            b) docker-compose -v\
3) In terminal from the project's root directory run the following command to load Anythink's backend and frontend:- docker-compose up
4) To check if docker is working correctly(i.e.the backend should be running and able to connect to your local database), test it by visiting http://localhost:3000/api/ping
5) Now, to check if the frontend is connected to the backend, go to http://localhost:3001/register and create a new user

AND THE SETUP IS COMPLETE, UP AND RUNNING!!!
            
