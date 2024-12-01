# Heuristics : Online-Judge | Online-Coding-Platform | (MERN-Based Website)

- Build a platform that remotely runs and compiles user submitted code for a programming problem securely and judges if the code is correct/wrong
- Provided access to users to keep track of submitted code by maintaining Leaderboard and history of submissions
- Used Docker and Sandboxing techniques to make online judge more secure
- Used Poling and Queue to handle multiple requests
- Deployed and can be used by many users by Horizontal Scaling

## Run Online-Judge Locally

- Navigate to client directory and install all dependencies for client side code using command : `npm install` and then run `npm start` to run react on [PORT 3000](https://localhost:3000)
- Navigate to the server directory and install the dependencies using the command `npm install`
- To run the server you must have `Docker` and `Redis` version greater than or equal to `2.8.18` installed on your PC
- If you are using Windows, install WSL for using `redis-server` and use `Docker-Desktop` for using `Docker`
- Server also uses `MongoDB`, either you can use mongodb-local or mongodb-atlas
- To use mongodb-atlas create a `.env` file and define a key named `DB_URL` and its value will be your atlas URL. To use mongodb-local no need to define `DB_URL` in `.env`
- Server uses cookies to handle authentication, which uses `JWT_SECRET` which is also defined in the `.env` file
- After all these steps you are all set to run the server. Use the command `npm start`. The server will start on [PORT 5000](https://localhost:5000)

## Problemset Page
![mainPage](https://github.com/user-attachments/assets/2e028c29-671c-4488-9fb4-b2180b031592)

## Problem Page
![ProblemPage](https://github.com/user-attachments/assets/be0dc23a-b335-449c-8df4-6cc1737157af)

## Code Editor
![Editor](https://github.com/user-attachments/assets/e9cc6c7c-02c4-4081-b140-0fa04ab13a9f)
