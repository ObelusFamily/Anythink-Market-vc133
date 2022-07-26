# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

<br />

[Install Docker](https://anythink.wilco.gg/chat/head-of-rd#:~:text=first%20thing%E2%80%99s%20first%20%2D-,install%20Docker.,-11%3A18)

<br />

 Verify docker is ready by running the following commands in your terminal: 
 
```
docker -v   
docker compose -v
```
<br />

Load Anythink's backend and frontend by running the command bellow from the project root directory
```
docker compose up
``` 

<br />

If Docker is working correctly, the backend should be running and able to connect to your local database.   
Test this by pointing your browser to [http://localhost:3000/api/ping](http://localhost:3000/api/ping)

<br />

Create a new user on [http://localhost:3001/register](http://localhost:3001/register)

<br />

Make sure that you run all scripts in the next quests on one of the containers created by ```docker-compose up```.  
Also, you can use ```docker exec``` to run commands on a running container.
