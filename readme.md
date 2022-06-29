# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**Steps needed to install and run the repo on your machine:** 

Step 1: Clone the repository of Anythink-Market-p7wx0 in your local machine, it can be done by using following steps: 
        1. On GitHub.com, navigate to the main page of the repository.
        2. Above the list of files, click on **Code** Option.
        3. Copy the URL for the repository.
        4. Open Git. (If you don't have Git then download it first. Link for download: https://git-scm.com/download/win)
        5. Change the current working directory to the location where you want the cloned directory
        6. Type the following command: git clone <Paste URL you copied> and then click enter.
  
  Congrats!!! You are done with creating the clone of the repo on your machine.
  
Step 2: Install Docker (Link: https://docs.docker.com/get-docker/)
Note: After Installing Docker on your PC when you open the application in your machine, then if you do not have Windows Subsyatem for Linux Update then a pop up box will appear with the error meassge regarding this, and link for installing will also be given in that message, so make sure you go that link and first install that so that docker can run smoothly in your system.

Step 3: Now, you can verify docker is ready by running the following commands in your terminal: docker -v and docker-compose -v.
  
Step 4: Run docker-compose up from the project root directory to load Anythink's backend and frontend.
Note:  Install "Docker for Windows" and make sure it is running in the background before running docker-compose up.
  
If docker is working correctly, the backend should be running and able to connect to your local database and to check the frontend and make sure it’s connected to the backend. If everything is working properly, you’ll be able to create a new user on localhost.
  
Great!! Your environment is ready.

