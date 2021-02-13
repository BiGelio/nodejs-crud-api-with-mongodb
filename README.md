### nodejs-crud-api-with-mongodb

---

**_NodeJS CRUD API with MongoDB_**

You can run this application in your system by cloning this repository and run the following commands through your terminal:

run `git clone https://github.com/BiGelio/nodejs-crud-api-with-mongodb.git` here you can use the way that fit for you

run `cd nodejs-crud-api-with-mongodb` \
run `touch .env` in this file you will have to add `DB` variable and assign it to your mongodb connection url \
run `npm install` \
run `node server.js`

To interact with this application once the server is running you can access it the following endpoints with your favorite tool

---

## POST localhost:5000/api/notes

Ex: ` { "title":"", "description":"" }`

## GET localhost:5000/api/notes

## GET localhost:5000/api/notes/:id get by id

## UPDATE localhost:5000/api/notes/:id

## DELETE localhost:5000/api/notes/:id
