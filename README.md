# React/Node Boilerplate

  This repo contains some boilerplate code for an application that uses Node on the back end and React on the front end. 

## Credit

   Most of this is shamelessly ripped off from the guys over at Fullstack React. 

   - See their blog post about it [here](https://www.fullstackreact.com/articles/using-create-react-app-with-a-server/)
   - See the corresponding repo [here](https://github.com/fullstackreact/food-lookup-demo)


   I use the create-react-app package for the React half of it. Find more on it [here](https://github.com/facebookincubator/create-react-app)

## Tech 

### Development

    Separate servers run concurrently for development. For React, a webpack server runs to transpile React's modules, ES6, etc. to happy, browser-ready javascript. For node, an express server runs as usual. 

    Running `npm start` from the project root will get everything up and running for you.

### Production

    The backend server is more or less the same on production as on development. 

    The webpack server can be configured for production by running `npm run build` in the ./client directory. This will compile all the front end goodness to the ./client/build folder as static assets. Host these assets from wherever, point them to your server, and you'll be up and running!

### Where's my Webpack config?

    The create-react-app package does a lot for you, but it also obfuscates a lot away from you in the process. If you want to dig in to your configs a bit more on the React side, just run `npm run eject` in the ./client directory.

