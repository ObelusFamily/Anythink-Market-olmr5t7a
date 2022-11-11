# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

At Anythink, our engineers work with a development environment that's hosted in the cloud called Github Codespace. No need to install anything on your own computer!
9:21
It takes about a minute to boot. Once it's up and ready you can start working directly in the browser or use VS Code to connect to the codespace in the cloud.
9:21
Go ahead and create your own codespace , I'll wait.
9:21
(No need to change anything in the default options, just click on the Create codespace button and wait for it to boot)
9:23
Great! Looks like your codespace is up and running. You can now run docker-compose up in your codespace's terminal to load Anythink's backend and frontend.
9:23
Once docker-compose finishes loading up, the backend should be running and able to connect to the database.
9:23
After the server is up, make sure you test it by pointing your browser to https://parkerbenbow-humble-cod-679jrw4rrqv2xxwv-3000.preview.app.github.dev/api/ping

Ness
9:34 PM
Easy Peasy! The backend is up and running.
9:34
Now, it’s time to check the frontend and make sure it’s connected to the backend.
9:34
If everything is working properly, you’ll be able to create a new user on https://parkerbenbow-humble-cod-679jrw4rrqv2xxwv-3001.preview.app.github.dev/register
9:34
Create one (choose a cool nickname and everything) and you’ll be able to move to the next task.
9:34
Ooohh, I didn’t expect you to do this so quickly! Even your username, benbowpg, brings back memories. Strangely enough, they’re your memories, which I don’t know why I have.
9:35
Never mind that, though—you’re done with this dib.
9:35
Just make sure that you run all scripts in the next quests on one of the containers created by docker-compose up.  Also, you can use docker exec to run commands on a running container.