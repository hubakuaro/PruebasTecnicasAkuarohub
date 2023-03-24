# NestJSApp

This is a miniproject with NestJS using a containerized postgres database

first install all the dependencies:

npm install

deploy database instance in our localhost with: (remember to use bash as it is executing a bash script)

npm run start:dev:db

enter into the instance and create the database that we will connect to our TypeOrm module with:

psql -U postgres 1234
CREATE DATABASE users;

execute easily with:

npm run start:dev

Try endpoints with Thunder Client (personal recommendation) :D
 
