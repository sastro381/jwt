# Json Web Token Implementation 
JWT on ExpressJS API 

## Setup 
**Database Config** 
- lookad configDatabase.json on app/config/ and change the database credential
- run `sequelize db:migrate` 

in this project we use MySQL as database (mysql2 library), if you want to use other database, please install db adapter via npm. for example if you use PostgreSQL run `npm install --save pg pg-hstore` or `npm install --save sqlite3` for SQLite or `npm install --save tedious` for MsSQL. 

**Project Config** 
- `npm install` 
- `sequelize init` 
- `touch .env` 
- put TITLE, NODE_ENV, URL, PORT dan SECRET params on .env file 

## Run
type `npm start` or `node server` on your terminal 
