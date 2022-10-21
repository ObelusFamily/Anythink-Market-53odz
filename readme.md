# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

## Project Setup Instructions
1. Before following through this step head over to https://git-scm.com/book/en/v2/Getting-Started-Installing-Git to install git on your local machine

2. After installation, open a terminal and verify that you have successfully installed git by running the command ```git --version```

3. Open a terminal of your choice could be **Command Prompt**, **Windows Powershell**, **Bash** or **ZSH** and  run the command ```git clone git@github.com:ObelusFamily/Anythink-Market-53odz.git``` to clone this repository

4. Ensure that you have both Docker and docker-composer installed on your computer for the next set of steps you will take

5. Navigate into the project directory by running the command ```cd Anythink-Market-53odz```

6. Boot up the local development server by running the command ```docker-compose up``` This will start up all the components of the application from the frontend to the Backend and the database