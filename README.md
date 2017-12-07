# iPlant Status Site

This is currently running here: <http://status.iplantcollaborative.org/>

The intention of this web-app is to determine which services are currently operational.  One can subscribe to downtime notifications for each respective service.  This App is currently hosted via Heroku, as it is completely outside of our infrastructure and can accurately determine operability of our services.

## Development

First create a fork of this repo (fork button in upper right corner).

Clone your fork.
```
git clone git@github.com:<username>/status-site.git
```

Navigate into the project and install dependencies.
```
cd status-site;
npm i
```

Start web app.
```
npm run start 
```

## Deployment with Heroku
This App is configured to work directly with Heroku and thus requires specific package definitions and dependencies to "deploy" with Heroku.  One of these dependencies is [Sails](http://sailsjs.org).
