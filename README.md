# Exercises

Connect to this database below and complete all of these requirements:

mongo mongodb+srv://student:coderschool@cluster0-frbsv.mongodb.net/restaurants
You can also use the string

mongodb+srv://student:coderschool@cluster0-frbsv.mongodb.net/restaurants
to connect through MongoDB Compass.

Database information
Database name: restaurants
Collection: rest
Document structure:
{
"address": {
"building": "1007",
"coord": [ -73.856077, 40.848447 ],
"street": "Morris Park Ave",
"zipcode": "10462"
},
"borough": "Bronx",
"cuisine": "Bakery",
"grades": [
{ "date": { "$date": 1393804800000 }, "grade": "A", "score": 2 },
{ "date": { "$date": 1378857600000 }, "grade": "A", "score": 6 },
{ "date": { "$date": 1358985600000 }, "grade": "A", "score": 10 },
{ "date": { "$date": 1322006400000 }, "grade": "A", "score": 9 },
{ "date": { "$date": 1299715200000 }, "grade": "B", "score": 14 }
],
"name": "Morris Park Bake Shop",
"restaurant_id": "30075445"
}

## Complete these 8 exercises:

- [x] 1. display the fields restaurant_id, name, borough and cuisine, but exclude the field \_id for all the documents in the collection restaurant.

- [] 2. display all the restaurant which is in the borough Bronx.

- [] 3. display the first 5 restaurant which is in the borough Bronx (hint: limit()).

- [] 4. display the next 5 restaurants after skipping first 5 which are in the borough Bronx (hint: skip()).

- [] 5. find the restaurants that achieved a score of more than 80 but less than 100.

- [] 6. find the restaurants that do not prepare any cuisine American and their grade score is more than 70 and latitude less than -65.754168.

- [] 7. find the restaurants which do not prepare any cuisine American and achieve a grade point ‘A' and do NOT belong to the borough Brooklyn.

- [] 8. find the restaurants which belong to the borough Bronx and prepared either American or Chinese dish.

The cuisine American has a space at the end. Don't miss it!
