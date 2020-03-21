# WebAppSample

This is a sample project that can be used as a starting point for creating a full web app. The frontend will be written in [React.js](https://reactjs.org/), the backend will be a [Node.js](https://nodejs.org/) app hosting an [Express.js](https://expressjs.com/) webserver. Data will be stored using [MongoDB](https://www.mongodb.com/). The whole thing will be deployed on [Heroku](https://www.heroku.com/). Steps and explanations will be added to the `docs` folder as the project develops and more pieces are added.

## Setup

After cloning the repository, run `yarn build` from the repository's root directory to install all dependencies and build a production version of the frontend for the server to host.

## Developing

To develop, you can independently run `yarn start` from the server and client directories; each will launch the development version of front/backend that will work locally.

## Production

Production environments (in this case Heroku) will just need to run `yarn setup` for the build step and `yarn start` for the execution step (both from the root directory). This will start the server with the production config and the built version of the front-end.
