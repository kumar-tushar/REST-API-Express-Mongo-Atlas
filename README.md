### REST-API with Express.js, Node.js & MongoDB-Atlas
#
#### DB_URL https://rest-api-express-mongo-atlas.herokuapp.com/subscribers
#
### CRUD operations can be performed using Postman 👇

#### GET ALL REQUEST
https://rest-api-express-mongo-atlas.herokuapp.com/subscribers
#
#### GET UNIQUE REQUEST
https://rest-api-express-mongo-atlas.herokuapp.com/subscribers/unique_id
#
#### POST REQUEST (JSON)
https://rest-api-express-mongo-atlas.herokuapp.com/subscribers
```
{
    "name":"user_name",
    "subscribedToChannel":"channel_name"
}
```
#
####  PATCH REQUEST (JSON)
https://rest-api-express-mongo-atlas.herokuapp.com/subscribers/unique_id
```
{
    "name":"new_name"
}
```
##### or
```
{
    "subscribedToChannel":"new_channel_name"
}
```
##### or
```
{
    "name":"new_user_name",
    "subscribedToChannel":"new_channel_name"
}
```
#
#### DELETE REQUEST
https://rest-api-express-mongo-atlas.herokuapp.com/subscribers/unique_id
