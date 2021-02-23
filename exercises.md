- [x] 1. display the fields restaurant_id, name, borough and cuisine, but exclude the field \_id for all the documents in the collection restaurant.

  - db.rest.find({restaurant: 1}, {name: 1}, {borough: 1}, {cuisine: 1}, {\_id: 0}).pretty()

- [x] 2. display all the restaurant which is in the borough Bronx.

  - db.rest.find({borough: "Bronx"}).pretty()

- [] 3. display the first 5 restaurant which is in the borough Bronx (hint: limit()).

- [] 4. display the next 5 restaurants after skipping first 5 which are in the borough Bronx (hint: skip()).

- [] 5. find the restaurants that achieved a score of more than 80 but less than 100.

- [] 6. find the restaurants that do not prepare any cuisine American and their grade score is more than 70 and latitude less than -65.754168.

- [] 7. find the restaurants which do not prepare any cuisine American and achieve a grade point ‘A' and do NOT belong to the borough Brooklyn.

- [] 8. find the restaurants which belong to the borough Bronx and prepared either American or Chinese dish.

The cuisine American has a space at the end. Don't miss it!
