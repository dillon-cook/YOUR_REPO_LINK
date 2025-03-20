README FOR RAMEN RATING APP

The project is a code challange for a company. The project is a simple app that allows users to rate ramen restaurants
The app is built using Node.js, Express.js, and MongoDB. The app is deployed on Heroku.

The app has the following features:
1. Users can view all the ramen restaurants
2. Users can view the details of a ramen restaurant
3. Users can add a new ramen restaurant
4. Users can update the details of a ramen restaurant
5. Users can delete a ramen restaurant
6. Users can rate a ramen restaurant

The app has the following routes:
1. GET /ramen - to get all the ramen restaurants
2. GET /ramen/:id - to get the details of a ramen restaurant
3. POST /ramen - to add a new ramen restaurant
4. PUT /ramen/:id - to update the details of a ramen restaurant
5. DELETE /ramen/:id - to delete a ramen restaurant
6. POST /ramen/:id/rate - to rate a ramen restaurant

The app has the following models:
1. Ramen - to store the details of a ramen restaurant
2. Rating - to store the rating of a ramen restaurant by a user  

The app has the following controllers:
1. ramenController - to handle the routes related to ramen restaurants
2. ratingController - to handle the routes related to ratings

The app has the following repositories:
1. ramenRepository - to handle the database operations related to ramen restaurants
2. ratingRepository - to handle the database operations related to ratings

The app is available at https://ramen-rating-app.herokuapp.com/
My license is 

