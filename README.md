# Basic MERN Stack 

### Front-End - React + Redux

### Back-End - Node.js + Express.js

### DataBase - MongoDB

### Deploy and Monitor - PM2

### CI/CD - coming soon with Jenkins

To run it locally -

### Steps to run in development mode:-

1. Fork the repo and clone it.
2. Make sure you have `yarn` `nodejs` installed in your system.
3. You will also need to have a mongodb set up if you are going to use it.  It's not requiered though so you can also just comment out the code in server.js
4. Build React Client UI. From root `cd my-weather-app/src/client` && `sudo yarn install` & `sudo yarn run build`.
5. Change dir to server `cd ../server` and run `sudo yarn install`.
6. PM2 should be installed alread, but just incase it isn't then you can set up pm2 with `yarn global add pm2` && `pm2 completion install`. 
7. Start up server `sudo NODE_ENV=production pm2 start server.js`. 
8. To monitor use `sudo pm2 monit`. To kill user `sudo pm2 kill`.

### Note: 
  UI uses proxy to reach server on port 5000


# Helper Comands:

##  Remove and reinstall node modules
##### rm -rf node_modules && npm install

## Run App
##### yarn start
