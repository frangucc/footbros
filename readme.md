## Versions Used

Node: 4.2.6
Ionic: 2.1.1
Cordova: 5.1.1
NPM: NVM Default for 4.2.6
Postgres: Current (9.2.+)

## How to Run 

Pre-Requsites: 

Create a psql database called rc1. 
Seed psql database with db dump `psql rc1 < path/to/seed`

** DO NOT FORGET TO SET PERMISSIONS FOR DATABASE FOR YOUR MAC OSX USER TO GRANT ALL **

1) Gulp
2) Ionic Build
3) Nodemon
4) Set Useragent to mobile (otherwise desktop renders an angular auth0 depenancy error)

## Versions Used

Node: 4.2.6
Ionic: 2.1.1
Cordova: 5.1.1
NPM: NVM Default for 4.2.6
Postgres: Current (9.2.+)

## How to Run 

Pre-Requsites: 

Create a psql database called rc1. 
Seed psql database with db dump `psql rc1 < path/to/seed`

** DO NOT FORGET TO SET PERMISSIONS FOR DATABASE FOR YOUR MAC OSX USER TO GRANT ALL **

1) Gulp
2) Ionic Build
3) Nodemon
4) Set Useragent to mobile (otherwise desktop renders an angular auth0 depenancy error)

## What was wrong? 

Socket.io was missing from the project. 

The browser HAS to have a mobile user agent. 

The urls for the search bar (React) were pulling from the wrong url. root.scope needed to be deleted in angular and the react data service needed to be refactored to pull from the right DB.


