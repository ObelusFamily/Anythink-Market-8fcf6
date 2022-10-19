# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

*Start working directly in the browser or use VS Code to connect to the codespace in the cloud.  Create your own codespace, no need to change anything in the default options, just click on the Create codespace button and wait for it to boot).

 * Looks like your codespace is up and running. You can now run docker-compose up in your codespace's terminal to load Anythink's backend and frontend.
 
 * Once docker-compose finishes loading up, the backend should be running and able to connect to the database.
 
*After the server is up, make sure you test it by pointing your browser to https://obelusfamily-anythink-market-8fcf6-xqr9xrr6jg9cjp9-3000.githubpreview.dev/api/ping

*Now, it’s time to check the frontend and make sure it’s connected to the backend.

If everything is working properly, you’ll be able to create a new user on https://obelusfamily-anythink-market-8fcf6-xqr9xrr6jg9cjp9-3001.githubpreview.dev/register

*Create one (choose a cool nickname and everything) and you’ll be able to move to the next task.

*Just make sure that you run all scripts in the next quests on one of the containers created by docker-compose up.  Also, you can use docker exec to run commands on a running container.
