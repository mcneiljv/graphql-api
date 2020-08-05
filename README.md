# graphql-api

A GraphQl API from scratch with Node JS, Express, and MongoDB.

## Run the project

1. yarn install
2. Create a cluster, db, and db user on MongoDB
3. Create nodemon.json file and insert MongoDB env variables like so:
   {
   "env": {
   "MONGO_USER": "your_username",
   "MONGO_PASSWORD": "your_password",
   "MONGO_DB": "your_database"
   }
   }
4. yarn start
5. If all goes well, visit http://localhost:3000/graphql to begin utilizing the API to add articles to your db.
