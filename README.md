# ChatApp
Node + Postgres + React + Socket demo app

## backend setup
  1. Create a database with name `chat_app`.
  2. `cd backend`
  3. create `.env` file and add below content in it. and replace username and password.
```
DB_HOST='localhost'
DB_NAME='chat_app'
DB_USERNAME=<username>
DB_PASSWORD=<password>
```
  4. `npm install`
  5. `npx sequelize-cli db:migrate`
  6. `npm start`

## frontend setup
  1. `cd frontend`
  2. `npm install`
  3. `npm start`
