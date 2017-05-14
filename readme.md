fix the pop-up to redirect
set menu in spree to be same as login
add active admin to rails app

get sprangular running

install postgres

npm install

gulp coffee    //load scripts

https://github.com/auth0/auth0-sso-sample/tree/master/app2.com

cat database_copy.sql | heroku pg:psql



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
